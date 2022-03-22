#include <stdio.h>
#include <conio.h>
#include <iostream>
#include <string>
using namespace std; 
void yaz()
{
	printf("Hello World\n");
}
  void yazr(int gelen)
  {
  	printf(" %d\n",gelen );
	}
	void yazc(string gelen )
	{
	//printf("%s\n",gelen);
	cout<<gelen;	
	  }
	  string yaz_ad(string ad)
	  {
	  	return "Hosgeldiniz sayin "+ad;  
		}  
float islem_yap(float s1,float s2,char islem)
{
	
		float sonuc=0;
	switch(islem)
	
  

	printf("1.sayiyi giriniz:");
	scanf("%f",&s1);
	printf("2.sayiyi giriniz:");
	scanf("%f",&s2);
		printf("Islemi giriniz:(+,-,*)");
		scanf("%c",&islem);
		
		
		s=islem_yap(s1,s2,islem);
	
	printf("Islem sonucu: %.2f\n",s);
	
	
}
float islem_yap(float s1,float s2,char islem)
{
	float sonuc=0;
	switch(islem)
	{
		case '+':sonuc=s1+s2;break;
		case '-':sonuc=s1-s2;break;
		 case '*':sonuc=s1*s2;break;
		 case '/':sonuc=s1/s2;break;
		 default: yazc("Hatali islem tipi\n");
		  
	}
return sonuc;
}
 main()
	
 {
  

	/*float s1,s2;
	float toplam,fark,carpim;
	float bolum;
	printf("1.sayiyi giriniz:");
	scanf("%f",&s1);
	printf("2.sayiyi giriniz:");
	scanf("%f",&s2);
	toplam=s1+s2;
		fark=s1-s2;
			carpim=s1*s2;
				bolum=s1/s2;
				printf("Toplama islemi sonucu:%.2f\n",toplam);
	printf("Cikarma islemi sonucu: %.2f\n",fark);
	printf("Carpim islemi sonucu: %.2f\n",carpim);
	printf("Bolum islemi sonucu: %.3f\n",bolum);*/
	/*float s1,s2;
	float sonuc=0;
	char islem;
	
  

	printf("1.sayiyi giriniz:");
	scanf("%f",&s1);
	printf("2.sayiyi giriniz:");
	scanf("%f",&s2);
		printf("Islemi giriniz:(+,-,*)");
		scanf("%c",&islem);
		
		if(islem=='+')
		sonuc=s1+s2;
			else if(islem=='-')
		sonuc=s1-s2;
		else if(islem=='*')
		sonuc=s1*s2;
		else if(islem=='/')
		sonuc=s1/s2;
		else
		printf("Yanlis islem\n");
	
	printf("Islem sonucu: %.2f\n",sonuc);*/
	//printf("Merhaba Dunya");
	/*yaz();
	for(int i=0;i<10;i++)
	yaz();*/
	/*yaz();
	yazr(5);
	yazr(10);
	yazc("Kursat");*/
	//string gelen=yaz_ad("Kursat");
	//printf("%s",gelen);
	//cout<<gelen;
	yap();

	
	
}
