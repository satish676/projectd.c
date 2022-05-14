# projectd.c

#include<stdio.h>
#include<string.h>

int main ()
{
	FILE *fp;

	char str[50]= "anvyaha";

	fp =  fopen ("satish.txt" ,"W");

	if (fp == null)
	{
		printf("fail failed to open\n");
	}
	else 
	{
		printf("fail is opende\n");
	}

	if ( strlen (str)>0)
	{

	     fputs( str , fp);
	     fputs("\n"fp);
	}

	fclose(fp);

	printf("data sucessfully writen \n");

	printf("the file will be closed\n");
}
