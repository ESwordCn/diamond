void diamond(int u_number, char* u_c, int choice)
{
    //参数1是符号个数,参数2是指定字符,参数3是选择行数还是最多行数量

    int c,c1,line_n,u_c_len;
    line_n=(u_number+1)/2;
    u_c_len=strlen(u_c);
    if(choice)
        line_n=u_number;

    for(c1=0; c1<line_n; c1++)
    {
        for(c=0; c<u_c_len*(line_n-1-c1); c++)
            printf(" ");
        for(c=0; c<(c1+1)*2-1; c++)
            printf("%s",u_c);
        printf("\n");
    }

    for(c1=line_n-1; c1>0; c1--)
    {
        for(c=0; c<u_c_len*(line_n-c1); c++)
            printf(" ");
        for(c=0; c<c1*2-1; c++)
            printf("%s",u_c);
        printf("\n");
    }
}

int main()
{
    diamond(5,"ESword",0);
    diamond(5,"稳",1);
}
