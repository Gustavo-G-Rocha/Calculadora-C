//calculadora em C
//projeto calculçadora
#include <stdio.h>
#include <locale.h>
#include <math.h>
int main()
{
    setlocale(LC_ALL, "Portuguese");
    system("color a");

        int op,  rodagem=1, proseguir;

        while(rodagem==1)
        {
            printf_s("\n\n\n");
            printf("\n Digite 0 para sair, 1 para entrar ");
            printf("\n(Todos os dados serão apagados )\n");
            scanf("%d", &proseguir);
            system("cls");
            if(proseguir==0)
            {
                rodagem=0;
            }
            else
            {
                printf("0 para sair \n");
                printf("1 Para caculadora \n");
                printf("2 Para equação de segundo grau \n");
                printf("3 Para teorema de Pitagoras \n");
                printf("4 Para perimetro \n");
                printf("5 Para area de polígonos  \n");
                printf("6 Para probabilidade \n");
                printf("7 Para calcular IMC \n");
                printf("8 Para calcular Investimento com juros simples \n");
                printf("9 Para calcular Emprestimo com juros simples\n");
                printf("10 Para calcular Investimento com juros compostos \n");
                printf("11 Para calcular Emprestimo com juros compostos \n");
                printf("12 Para conversor de velocidade \n");
                printf("13 Para conversor de massa \n");
                printf("14 Para conversor de temperatura \n");
                printf("15 Para conversor de comprimento \n");
                printf("16 Para conversor de area \n");
                printf("17 Para conversor de volume \n");
                printf("18 Para conversor de dados \n");
                printf("19 Para conversor de tempo \n");
                printf("20 Para achar numeros primos \n");
                printf("21 Para conversor binário \n");
                scanf("%d", &op);
                system("cls");
                if(op==0)
                {
                    rodagem=0;
                }
                if(op==1)
                {
                    chamafuncao1();
                }
                if(op==2)
                {
                    chamafuncao2();
                }
                if(op==3)
                {
                    chamafuncao3();
                }
                if(op==4)
                {
                    chamafuncao4();
                }
                if(op==5)
                {
                    chamafuncao5();
                }
                if(op==6)
                {
                    chamafuncao6();
                }
                if(op==7)
                {
                    chamafuncao7();
                }
                if(op==8)
                {
                    chamafuncao8();
                }
                if(op==9)
                {
                    chamafuncao9();
                }
                if(op==10)
                {
                    chamafuncao10();
                }
                if(op==11)
                {
                    chamafuncao11();
                }
                if(op==12)
                {
                    chamafuncao12();
                }
                if(op==13)
                {
                    chamafuncao13();
                }
                if(op==14)
                {
                    chamafuncao14();
                }
                if(op==15)
                {
                    chamafuncao15();
                }
                if(op==16)
                {
                    chamafuncao16();
                }
                if(op==17)
                {
                    chamafuncao17();
                }
                if(op==18)
                {
                    chamafuncao18();
                }
                if(op==19)
                {
                    chamafuncao19();
                }
                if(op==20)
                {
                    chamafuncao20();
                }
                if(op==21)
                {
                    chamafuncao21();
                }


            }

    }
    return(0);
}

int chamafuncao1()
{
                float memoria=0, opescolhida=0, valor1=0, valor2=0, rodagemmemoria=0, parada;

                printf("Digite 1 para adição \n");
                printf("Digite 2 para subtração \n");
                printf("Digite 3 para multiplicação \n");
                printf("Digite 4 para divisão \n");
                printf("Digite 5 para potenciação \n");
                printf("Digite 6 para radicação ao quadrado \n");
                printf("Digite 0 para sair \n\n");
                scanf("%f", &opescolhida);


                if(opescolhida==0)
                {
                rodagemmemoria=0;
                }
                if(opescolhida==1)
                {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);
                  printf("\n Valor 2 \n");
                  scanf("%f", &valor2);
                  memoria= valor1+ valor2;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;

              }
            if(opescolhida==2)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);
                  printf("\n Valor 2 \n");
                  scanf("%f", &valor2);
                  memoria= valor1- valor2;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;

              }
              if(opescolhida==3)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);
                  printf("\n Valor 2 \n");
                  scanf("%f", &valor2);
                  memoria= valor1 * valor2;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;
              }
             if(opescolhida==4)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);
                  printf("\n Valor 2 \n");
                  scanf("%f", &valor2);
                  memoria= valor1 / valor2;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;

              }
            if(opescolhida==5)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);
                  printf("\n Valor 2 \n");
                  scanf("%f", &valor2);
                  memoria=pow(valor1,valor2);

                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;

              }
            if(opescolhida==6)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);
                  memoria= sqrt(valor1);
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;

              }


            while(rodagemmemoria==1)
            {
            system("cls");
            printf("\n\n  [%f] \n\n", memoria );
            printf("Digite 0 para sair \n");
            printf("Digite 1 para adição \n");
            printf("Digite 2 para subtração \n");
            printf("Digite 3 para multiplicação \n");
            printf("Digite 4 para divisão \n");
            printf("Digite 5 para potenciação  \n");
            printf("Digite 6 para radicação ao quadrado \n");
            scanf("%f", &opescolhida);

            if(opescolhida==0)
            {
                rodagemmemoria=0;
            }
            if(opescolhida==1)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);

                  memoria= (memoria)+valor1;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;
              }
            if(opescolhida==2)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);

                  memoria= (memoria)-valor1;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;
              }
              if(opescolhida==3)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);

                  memoria= (memoria)*valor1 ;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;
              }
             if(opescolhida==4)
              {
                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);

                  memoria= (memoria) / valor1;
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;
              }
            if(opescolhida==5)
              {


                  printf("\n Valor 1   \n");
                  scanf("%f", &valor1);

                  memoria=pow(memoria,valor1);
                  printf("\n [%f]", memoria);
                  rodagemmemoria=1;
              }
            if(opescolhida==6)
              {

                  memoria= sqrt(memoria);
                  printf("\n [%f] ", memoria);
                  rodagemmemoria=1;
              }
             }
            main();

            }
int chamafuncao2()
{
    double r1, r2;
    float a, b, c, d, Xv, Yv;
        printf("\n\n informe A \n");
        scanf("%f", &a);
        printf("\n\n informe B \n");
        scanf("%f", &b);
        printf("\n\n informe C \n");
        scanf("%f", &c);
        d= (b * b)+ (-4 * a * c);
        if(d < 0)
        {
            printf("\n\n Nao possivel, delta negativo ");
        }
        else
        {
            r1= (-b + sqrt(d)) / (2 * a);
            r2= (-b - sqrt(d)) / (2 * a);
            printf("\n\n As raizes são %f, %f", r1, r2);

        }
        Xv=-1*(b/2*a);
        Yv=-1*(d/4*a);
        printf("\n O delta é %f", d);
        printf("\n O X vertice é %f", Xv);
        printf("\n O Y vertice é %f", Yv);

            main();
        }
int chamafuncao3()
{

    float cateto1, cateto2, hipotenusa, oppitagoras=0, auxpitagoras;
    printf("\nDeseja encontrar hipotenusa digite 0 \n");
    printf("Deseja encontrar cateto digite 1 \n");
    scanf("%f", &oppitagoras);
    if(oppitagoras==0)
    {
        printf("\n Informe o cateto \n ");
        scanf("%f", &cateto1);
        printf("\n Informe o cateto \n ");
        scanf("%f", &cateto2);
        auxpitagoras=(cateto1*cateto1)+(cateto2*cateto2);
        hipotenusa=sqrt(auxpitagoras);
        printf("\n Hipotenusa %f", hipotenusa);
    }
        if(oppitagoras==1)
    {
        printf("\n Informe o hipotenusa \n ");
        scanf("%f", &hipotenusa);
        printf("\n Informe o cateto \n ");
        scanf("%f", &cateto2);
        auxpitagoras=(hipotenusa*hipotenusa)-(cateto2*cateto2);
        cateto1=sqrt(auxpitagoras);
        printf("\n Cateto %f", cateto1);
    }
    main();
    }
int chamafuncao4()
{
    float ladosdeperimetro, quantidadesladosdeperimetro, perimetrototal, casoperimetro;
    printf("\n\nInforme 1 para circulo \n");
    printf("\nInforme 2 para polígonos \n");
    scanf("%f", &casoperimetro);
    if(casoperimetro==1)
    {
        printf("\nInforme o diametro \n");
        scanf("%f", &ladosdeperimetro);
        perimetrototal=ladosdeperimetro*3.14159265359;
        printf("\nPerimetro circular %f \n", perimetrototal);
    }
    if(casoperimetro==2)
    {
        printf("\nInforme a quantidades de lados\n");
        scanf("%f", &quantidadesladosdeperimetro);
        printf("\nInforme o tamnaho de cada lado\n");
        scanf("%f", &ladosdeperimetro);
        perimetrototal=quantidadesladosdeperimetro*ladosdeperimetro;
        printf("\nPerimetro  %f \n", perimetrototal);
    }
    main();
}
int chamafuncao5()
{
     float raioarea, areatotal, lado1area, lado2area, oparea, quant, tamanho, apotema, perimetro;
    printf("\n1 Para area de circulo");
    printf("\n2 Para area de retangulo");
    printf("\n3 Para area de triangulo");
    printf("\n4 Para area de trapezio");
    printf("\n5 Para area de losango");
    printf("\n6 Para demais formas \n\n");
    scanf("%f", &oparea);
    if(oparea==1)
    {
        printf("\nInforme o raio do circulo \n");
        scanf("%f", &raioarea);
        areatotal= (raioarea*raioarea)*3.14159265359;
        printf("\nArea do circlo %f", areatotal);
    {
        printf("\n Informe um lado do retangulo \n");
        scanf("%f", &lado1area);
        printf("\n Informe um lado do retangulo \n");
        scanf("%f", &lado2area);
        areatotal=lado1area*lado2area;
        printf("\nArea do retangulo %f", areatotal);
    }
    if(oparea==3)
    {
        printf("\n Informe um lado do triangulo \n");
        scanf("%f", &lado1area);
        printf("\n Informe um lado do triangulo \n");
        scanf("%f", &lado2area);
        areatotal=(lado1area*lado2area)/2;
        printf("\nArea do triangulo %f", areatotal);
    }
    if(oparea==4)
    {
        printf("\n Informe a base maior do trapezio \n");
        scanf("%f", &lado1area);
        printf("\n Informe a base menor do trapezio \n");
        scanf("%f", &lado2area);
        printf("\n informe a altura do trapezio \n");
        scanf("%f", &raioarea);
        areatotal=((lado1area+lado2area)*raioarea)/2;
        printf("\nArea do trapezio %f", areatotal);
    }
    if(oparea==5)
    {
        printf("\n Informe a diagonal maior do losango \n");
        scanf("%f", &lado1area);
        printf("\n Informe a diagonal menor do losango \n");
        scanf("%f", &lado2area);
        areatotal=(lado1area+lado2area)/2;
        printf("\nArea do losango %f", areatotal);
    }
    if(oparea==6)
    {
        printf("\n Informe quantidades de lados \n");
        scanf("%f", &quant);
        printf("\n Informe tamanho dos lados \n");
        scanf("%f", &tamanho);
        printf("\n Informe apotema\n");
        scanf("%f", &apotema);
        perimetro=(quant*tamanho);
        areatotal=(perimetro*apotema)/2;
        printf("\nArea de %f", areatotal);
    }
    main();
}
}
int chamafuncao6 ()
{
        float infoprobabilidade, probabilidade;
        printf("\n Informe uma quantidade para gerar probabilidade \n ");
        scanf("%f", &infoprobabilidade);
        probabilidade=100/infoprobabilidade;
        printf("\n %f Porcento de chance \n", probabilidade);
        main();
}
int chamafuncao7()
{
    setlocale(LC_ALL, "Portuguese");
    system("color 0a");
    float imc, pesoimc, alturaimc;
    printf("\n Informe altura em metros \n");
    scanf("%f", &alturaimc);
    printf("\n Informe peso \n");
    scanf("%f", &pesoimc);
    imc=pesoimc/(alturaimc*alturaimc);
    if(imc>18 && imc<25)
    {
        printf("\n Peso normal %f \n\n", imc);
    }
        if(imc>=25)
    {
        printf("\n Sobrepeso %f \n\n", imc);
    }
     if(imc<=18)
    {
        printf("\n Subpeso %f \n\n", imc);

    }
    main();
}
int chamafuncao8()
{


    int   duracaoinvestimento, whileinvest=0, apoioinvest=0;
    float investimentofeito, jurosmensais,valorfinalinvestimento;
       printf("\n Infomre o valor de investimento \n");
    scanf("%f", &investimentofeito);
    printf("\n Infomre os juros mensais \n");
    scanf("%f", &jurosmensais);
    printf("\n Informe quantidade de meses de investimento \n");
    scanf("%d", &duracaoinvestimento);
    valorfinalinvestimento=investimentofeito;
    jurosmensais=jurosmensais/100;

        while(whileinvest==0)
        {
            apoioinvest=apoioinvest+1;

           valorfinalinvestimento=valorfinalinvestimento+(investimentofeito*jurosmensais);
            if(apoioinvest==duracaoinvestimento)
            {

                whileinvest=1;
            }

        }

    printf("\n Em %d meses ", duracaoinvestimento);
    printf("com o valor final de %f", valorfinalinvestimento);


    main();

}
int chamafuncao9()
{

    int   duracaoemprestimo, whileemprestimo=0, apoioemprestimo=0;
    float emprestimofeito, jurosmensaisemprestimo,valorfinalemprestimo;
       printf("\n Infomre o valor de emprestimo \n");
    scanf("%f", &emprestimofeito);
    printf("\n Infomre os juros mensais \n");
    scanf("%f", &jurosmensaisemprestimo);
    printf("\n Informe quantidade de meses de emprestimo \n");
    scanf("%d", &duracaoemprestimo);
    valorfinalemprestimo=emprestimofeito;
    jurosmensaisemprestimo=jurosmensaisemprestimo/100;

        while(whileemprestimo==0)
        {
            apoioemprestimo=apoioemprestimo+1;

           valorfinalemprestimo=valorfinalemprestimo+(emprestimofeito*jurosmensaisemprestimo);
            if(apoioemprestimo==duracaoemprestimo)
            {
                whileemprestimo=1;
            }

        }

    printf("\n Em %d meses ", duracaoemprestimo);
    printf("com o valor final de %f", valorfinalemprestimo);


    main();
}
int chamafuncao10()
{


    int   duracaoinvestimentoc, whileinvestc=0, apoioinvestc=0;
    float investimentofeitoc, jurosmensaisc,valorfinalinvestimentoc;
       printf("\n Infomre o valor de investimento \n");
    scanf("%f", &valorfinalinvestimentoc);

    printf("\n Infomre os juros mensais \n");
    scanf("%f", &jurosmensaisc);

    printf("\n Informe quantidade de meses de investimento \n");
    scanf("%d", &duracaoinvestimentoc);

    jurosmensaisc=jurosmensaisc/100;

        while(whileinvestc==0)
        {
            apoioinvestc=apoioinvestc+1;

           valorfinalinvestimentoc=valorfinalinvestimentoc+(valorfinalinvestimentoc*jurosmensaisc);
            if(apoioinvestc==duracaoinvestimentoc)
            {
                whileinvestc=1;
            }

        }

    printf("\n Em %d meses ", duracaoinvestimentoc);
    printf("com o valor final de %f", valorfinalinvestimentoc);


    main();

}
int chamafuncao11()
{

    int   duracaoemprestimoc, whileemprestimoc=0, apoioemprestimoc=0;
    float  jurosmensaisemprestimoc,valorfinalemprestimoc;
       printf("\n Infomre o valor de emprestimo \n");
    scanf("%f", &valorfinalemprestimoc);
    printf("\n Infomre os juros mensais \n");
    scanf("%f", &jurosmensaisemprestimoc);
    printf("\n Informe quantidade de meses de emprestimo \n");
    scanf("%d", &duracaoemprestimoc);

    jurosmensaisemprestimoc=jurosmensaisemprestimoc/100;

        while(whileemprestimoc==0)
        {
            apoioemprestimoc=apoioemprestimoc+1;

           valorfinalemprestimoc=valorfinalemprestimoc+(valorfinalemprestimoc*jurosmensaisemprestimoc);
            if(apoioemprestimoc==duracaoemprestimoc)
            {
                whileemprestimoc=1;
            }

        }

    printf("\n Em %d meses ", duracaoemprestimoc);
    printf("com o valor final de %f", valorfinalemprestimoc);


    main();
}
int chamafuncao12()
{
    float milhasporhoras, quilometrosporhoras, opvelocidade, mach, metroporsegundo, quilometrosporsegundo, no, polegadaporsegundo, peporsegundo;
    printf("\n Digite 1 para converte quilômetros por hora \n");
    printf(" Digite 2 para converte milhas por hora\n");
    printf(" Digite 3 para converte mach \n");
    printf(" Digite 4 para metros por segundos \n");
    printf(" Digite 5 para quilômetros por segundo \n");
    printf(" Digite 6 para nó \n");
    printf(" Digite 7 para polegada por segundo \n");
    printf(" Digite 8 para pé por segundo \n");
    scanf("%f", &opvelocidade);
    if(opvelocidade==1)
    {
        printf ("\n Informe a velocidade em quilometros por horas \n");
        scanf("%f", &quilometrosporhoras);
    }
    if(opvelocidade==2)
    {
        printf("\n Informe a velocidade em milhas por horas\n");
        scanf("%f", &milhasporhoras);
        quilometrosporhoras=milhasporhoras*1.609344;

    }
    if(opvelocidade==3)
    {
        printf("\n Informe a velocidade em mach \n");
        scanf("%f", &mach);
        quilometrosporhoras=mach*1225.08;


    }
    if(opvelocidade==4)
    {
        printf("\n Informe a velocidade em metros por segundos \n");
        scanf("%f", &metroporsegundo);
        quilometrosporhoras=metroporsegundo*3.6;
    }
    if(opvelocidade==5)
    {
        printf("\n Informe a velocidade em quilometros segundos \n");
        scanf("%f", &quilometrosporsegundo);
        quilometrosporhoras=quilometrosporsegundo*3600;


    }
    if(opvelocidade==6)
    {
        printf("\n Informe a velocidade em nó \n");
        scanf("%f", &no);
        quilometrosporhoras=no*1.852;
    }
    if(opvelocidade==7)
    {
        printf("\n Informe a velocidade em polegadas por segundos\n");
        scanf("%f", &polegadaporsegundo);
        quilometrosporhoras=polegadaporsegundo*20.25337183;

    }
    if(opvelocidade==8)
    {
        printf  ("\n Informe a velocidade em pé por segundo \n");
        scanf("%f", &peporsegundo);
        quilometrosporhoras=peporsegundo*1.68780986;

    }
    milhasporhoras=quilometrosporhoras/1.609344;
    quilometrosporhoras=milhasporhoras*1.609344;
    mach=quilometrosporhoras/1225.08;
    metroporsegundo=quilometrosporhoras/3.6;
    quilometrosporsegundo=quilometrosporhoras/3600;
    no=quilometrosporhoras/1.852;

    polegadaporsegundo=quilometrosporhoras/0.09144;
    peporsegundo=quilometrosporhoras/1.09728;

        printf("\n %f quilometros por hora", quilometrosporhoras);
        printf("\n %f milhas por hora", milhasporhoras);
        printf("\n %f mach", mach);
        printf("\n %f metros por segundo ", metroporsegundo);
        printf("\n %f quilometros por segundo", quilometrosporsegundo);
        printf("\n %f nó", no);
        printf("\n %f polegadas por segundo", polegadaporsegundo);
        printf("\n %f pé por segundo", peporsegundo);
    main();
}
int chamafuncao13()
{
    float lb, kg, opmassa, t, g, mg, mmg, q, oz, ct, gr, it, sht, cwtuk, cwtus, st, dr, dan, jin, qian, liang, jintw ;

    printf("\nDigite 1 para converte quilogramas \n");
    printf("Digite 2 para converte libra \n");
    printf("Digite 3 para converte tonelada \n");
    printf("Digite 4 para converte grama \n");
    printf("Digite 5 para converte miligrama \n");
    printf("Digite 6 para converte micrograma \n");
    printf("Digite 7 para converte quintal \n");
    printf("Digite 8 para converte onça \n");
    printf("Digite 9 para converte quilate \n");
    printf("Digite 10 para converte grão \n");
    printf("Digite 11 para converte tonelada britânica \n");
    printf("Digite 12 para converte tonelada norte americana \n");
    printf("Digite 13 para converte quintal britânico \n");
    printf("Digite 14 para converte quintal norte americano \n");
    printf("Digite 15 para converte pedra \n");
    printf("Digite 16 para converte dram \n");
    printf("Digite 17 para converte dan \n");
    printf("Digite 18 para converte jin \n");
    printf("Digite 19 para converte qian \n");
    printf("Digite 20 para converte liang \n");
    printf("Digite 21 para converte jin Taiwan \n");
    scanf("%f", &opmassa);
    system("cls");
    if(opmassa==1)
    {
        printf("\n Informe quantidade de quilogramas \n");
        scanf("%f", &kg);

    }
    if(opmassa==2)
    {
        printf("\n Informe quantidade de libras \n");
        scanf("%f", &lb);
        kg=lb*0.45359237;

    }
    if(opmassa==3)
    {
        printf("\n Informe quantidade de toneladas \n");
        scanf("%f", &t);
        kg=t*1000;

    }
    if(opmassa==4)
        {
        printf("\n Informe quantidade de gramas \n");
        scanf("%f", &g);
        kg=g*0.001;


    }
    if(opmassa==5)
    {
        printf("\n Informe quantidade de miligramas \n");
        scanf("%f", &mg);
        kg=mg*0.000001;


    }
   if(opmassa==6)
   {
       printf("\n Informe quantidade de micrograma \n");
        scanf("%f", &mmg);
        kg=mmg*0.000000001;

   }
   if(opmassa==7)
      {

    printf("\n Informe quantidade de quintal \n");
        scanf("%f", &q);
        kg=q*100;


}
   if(opmassa==8)
   {
       printf("\n Informe quantidade de onça \n");
        scanf("%f", &oz);
        kg=oz*0.0283495231;

   }
    if(opmassa==9)
    {
        printf("\n Informe quantidade de quilate \n");
        scanf("%f", &ct);
        kg=ct*0.0002;


    }
    if(opmassa==10)
    {
        printf("\n Informe quantidade de grão \n");
        scanf("%f", &gr);
        kg=gr*0.000064799;


    }
    if(opmassa==11)
    {
        printf("\n Informe quantidade de tonelada britânica \n");
        scanf("%f", &it);
        kg=it*1016.04691;

    }
    if(opmassa==12)
        {
        printf("\n Informe quantidade de tonelada americana \n");
        scanf("%f", &sht);
        kg=sht*907.18474;

    }
    if(opmassa==13)
        {
        printf("\n Informe quantidade de quintal britânico \n");
        scanf("%f", &cwtuk);
        kg=cwtuk*50.8023454;

    }
    if(opmassa==14)
        {
        printf("\n Informe quantidade de quintal americano \n");
        scanf("%f", &cwtus);
        kg=cwtus*45.359237;

    }
    if(opmassa==15)
        {
        printf("\n Informe quantidade de pedra \n");
        scanf("%f", &st);
        kg=st*6.35029318;
    }
    if(opmassa==16)
        {
        printf("\n Informe quantidade de dram \n");
        scanf("%f", &dr);
        kg=dr*0.0017718452;

    }
    if(opmassa==17)
    {

        printf("\n Informe quantidade de dan \n");
        scanf("%f", &dan);
        kg=dan*50;
    }
    if(opmassa==18)
        {
        printf("\n Informe quantidade de jin \n");
        scanf("%f", &jin);
        kg=jin*0.5;

    }
    if(opmassa==19)
        {
        printf("\n Informe quantidade de qian \n");
        scanf("%f", &qian);
        kg=qian*0.005;


    }
    if(opmassa==20)
        {
        printf("\n Informe quantidade de liang\n");
        scanf("%f", &liang);
        kg=liang*0.05;



    }
    if(opmassa==21)
        {
        printf("\n Informe quantidade de jin taiwan \n");
        scanf("%f", &jintw);
        kg=jintw*0.6;

    }
        t=kg*0.001;
        kg=t/0.001;
        lb=kg*2.20462262;
        g=kg*1000;
        mg=kg*1000000;
        mmg=1000000000;
        q=kg*0.01;
        oz=kg*35.2739619;
        ct=kg*5000;
        gr=kg*15432.3584;
        it=kg*0.000984206528;
        sht=kg*0.00110231131;
        cwtuk=kg*0.0196841306;
        cwtus=kg*0,0220462262;
        st=kg*0.157473044;
        dr=kg*564.383391;
        dan=kg*0.02;
        jin=kg*2;
        qian=kg*200;
        liang=kg*20;
        jintw=kg*1.66666667;

        printf("\n%f quilogramas \n", kg);
        printf("%f libra \n", lb);
        printf("%f tonelada \n", t);
        printf("%f grama \n", g);
        printf("%f miligrama \n", mg);
        printf("%f micrograma \n", mmg);
        printf("%f quintal \n", q);
        printf("%f onça \n", oz);
        printf("%f quilate \n", ct);
        printf("%f grão \n", gr);
        printf("%f tonelada britânica \n", it);
        printf("%f tonelada norte americana \n", sht);
        printf("%f quintal britânico \n", cwtuk);
        printf("%f quintal norte americano \n", cwtus);
        printf("%f pedra \n", st);
        printf("%f dram \n", dr);
        printf("%f dan \n", dan);
        printf("%f jin \n", jin);
        printf("%f qian \n", qian);
        printf("%f liang \n", liang);
        printf("%f jin Taiwan \n", jintw);

    main();
}
int chamafuncao14 ()
{
    float celsius, fahrenheit, optemp, kelvin, rankine, reaumur, newton, delisle, romer;
    printf("\n Digite 1 para converter Celsius \n");
    printf(" Digite 2 para converter Fahrenheit \n");
    printf(" Digite 3 para converter Kelvin \n");
    printf(" Digite 4 para converter Rankine \n");
    printf(" Digite 5 para converte Réaumur \n");
    printf(" Digite 6 para converter Newton \n");
    printf(" Digite 7 para converter Delisle \n");
    printf(" Digite 8 para converte Rømer \n");
    scanf("%f", &optemp);
    system("cls");
    if(optemp==1)
    {
        printf("\n Informe a temperatura em Celsius \n");
        scanf("%f", &celsius);

    }
    if(optemp==2)
    {
        printf("\n Informe a temperatura em Fahrenheit \n");
        scanf("%f", &fahrenheit);
        celsius=(fahrenheit-32)/1.8;

    }
    if(optemp==3)
    {
        printf("\n Informe a temperatura em Kelvin \n");
        scanf("%f", &kelvin);
        celsius=kelvin-273.15;


    }
    if(optemp==4)
    {
        printf("\n Informe a temperatura em Rankine \n");
        scanf("%f", &rankine);
        celsius=rankine*5/9 - 273.15;

    }
    if(optemp==5)
    {
        printf("\n Informe a temperatura em Réaumur \n");
        scanf("%f", &reaumur);


    }
    if(optemp==6)
    {
        printf("\n Informe a temperatura em Newton \n");
        scanf("%f", &newton);
        celsius=(newton)*100/33;
          }
    if(optemp==7)
    {

        printf("\n Informe a temperatura em Delisle \n");
        scanf("%f", &delisle);
          }
    if(optemp==8)
    {
        printf("\n Informe a temperatura em Rømer \n");
        scanf("%f", &romer);
        celsius=(romer-7.5)*1.9047619;

    }
        kelvin=celsius+273.15;
        celsius=kelvin-273.15;
        fahrenheit=(celsius*9/5) + 32;
        rankine=(celsius * 9/5) + 491.67;
        reaumur=celsius*4/5;
        romer= celsius*0.525+7.5;
        newton=(celsius)* 33/100;
        delisle=(100 - celsius) * 1.5;

        printf("\n %f Celsius", celsius);
        printf("\n %f Fahrenheit", fahrenheit);
        printf("\n %f Kelvin", kelvin);
        printf("\n %f Rankine", rankine);
        printf("\n %f Réaumur", reaumur);
        printf("\n %f Newton", newton);
        printf("\n %f Delisle", delisle);
        printf("\n %f Rømer", romer);


    main();

}
int chamafuncao15 ()
    {
        float opcomprimento, km, m, dm, cm, mm, mmm, nm, pm, nmi, mi, fur, ftm, yd, ft, in, gongli, li, chi, cun, zhang, fen, lii;
        printf("\n Digite 1 para converter metros");
        printf("\n Digite 2 para converter quilometros");
        printf("\n Digite 3 para converter decimetros");
        printf("\n Digite 4 para converte centimetros");
        printf("\n Digite 5 para converter milímetro");
        printf("\n Digite 6 para converter micrômetro");
        printf("\n Digite 7 para converter nanômetro");
        printf("\n Digite 8 para converter picômetro");
        printf("\n Digite 9 para converter milha náutica");
        printf("\n Digite 10 para converter milha");
        printf("\n Digite 11 para converter femara");
        printf("\n Digite 12 para converter fathom");
        printf("\n Digite 13 para converter jarda");
        printf("\n Digite 14 para converter pés");
        printf("\n Digite 15 para converter polegada");
        printf("\n Digite 16 para converter gongli");
        printf("\n Digite 17 para converter li");
        printf("\n Digite 18 para converter zhang");
        printf("\n Digite 19 para converter chi");
        printf("\n Digite 20 para converter cun");
        printf("\n Digite 21 para converter fen");
        printf("\n Digite 22 para converter lii \n");
        scanf("%f", &opcomprimento);
        system("cls");
        if(opcomprimento==1)
        {
            printf("\n Informe o comprimento em metro \n");
            scanf("%f", &m);

        }

        if(opcomprimento==2)
        {
            printf("\n Informe o comprimento em quilometros\n");
            scanf("%f", &km);
            m=km*0.001;

        }
        if(opcomprimento==3)
        {
            printf("\n Informe o comprimento em decimetro \n");
            scanf("%f", &dm);
            m=dm*10;

        }
        if(opcomprimento==4)
        {
            printf("\n Informe o comprimento em centimetros \n");
            scanf("%f", &cm);
            m=cm*100;

        }
        if(opcomprimento==5)
        {
            printf("\n Informe o comprimento em milímetro \n");
            scanf("%f", &mm);
            m=mm*1000;

        }
        if(opcomprimento==6)
        {
            printf("\n Informe o comprimento em micrômetro \n");
            scanf("%f", &mmm);
            m=mmm*1000000;

        }
        if(opcomprimento==7)
        {
            printf("\n Informe o comprimento em nanometro \n");
            scanf("%f", &nm);
            nm=m*1000000000;

        }
        if(opcomprimento==8)
        {
            printf("\n Informe o comprimento em picometro \n");
            scanf("%f", &pm);
            m=pm*10000*100000000;

        }
        if(opcomprimento==9)
        {
            printf("\n Informe o comprimento em milhas nautica\n");
            scanf("%f", &nmi);
            m=nmi*0.000539956803;

        }
        if(opcomprimento==10)
        {
            printf("\n Informe o comprimento em milhas\n");
            scanf("%f", &mi);
            m=mi*0.000621371192;

        }
        if(opcomprimento==11)
        {
            printf("\n Informe o comprimento em femara \n");
            scanf("%f", &fur);
            m=fur*0.00497096954;


        }
        if(opcomprimento==12)
        {

            printf("\n Informe o comprimento em fathom\n");
            scanf("%f", &ftm);
            m=ftm*0.546806649;

        }
        if(opcomprimento==13)
        {
            printf("\n Informe o comprimento em jarda \n");
            scanf("%f", &yd);
            m=yd*1.0936133;


        }
        if(opcomprimento==14)
        {
            printf("\n Informe o comprimento em pés \n");
            scanf("%f", &ft);
            m=ft*3.2808399;


        }
        if(opcomprimento==15)
        {
            printf("\n Informe o comprimento em polegadas \n");
            scanf("%f", &in);
            m=in*39.3700787;


        }
        if(opcomprimento==16)
        {
            printf("\n Informe o comprimento em gongli\n");
            scanf("%f", &gongli);
            m=gongli*0.001;

        }
        if(opcomprimento==17)
        {
            printf("\n Informe o comprimento em li \n");
            scanf("%f", &li);
            m=li*0.002;


        }
        if(opcomprimento==18)
        {
            printf("\n Informe o comprimento em zhang \n");
            scanf("%f", &zhang);
            m=zhang*0.3;

        }
        if(opcomprimento==19)
        {
            printf("\n Informe o comprimento em chi \n");
            scanf("%f", &chi);
            m=chi*3;

        }
        if(opcomprimento==20)
        {
            printf("\n Informe o comprimento em cun \n");
            scanf("%f", &cun);
            m=cun*30;

        }
        if(opcomprimento==21)
        {
            printf("\n Informe o comprimento em fen \n");
            scanf("%f", &fen);
            m=fen*300;

        }
        if(opcomprimento==22)
        {
            printf("\n Informe o comprimento em lii \n");
            scanf("%f", &lii);
            m=lii*3000;

        }
            km=m*1000;
            m=km/1000;
            dm=m*0.1;
            cm=m*0.01;
            mm=m*0.001;
            mmm=m*0.000001;
            nm=m*0.000000001;
            pm=m*0.000000000001;
            nmi=m*1852;
            mi=m*1609.344;
            fur=m*201.168;
            ftm=m*1.8288;
            yd=m*0.9144;
            ft=m*0.3048;
            in=m*0.0254;
            gongli=m*1000;
            li=m*500;
            zhang=m*3.33333333;
            chi=m*0.33333333;
            cun=m*0.03333333;
            fen=m*0.00333333;
            lii=m*0.00033333;

            printf("\n %f metros ", m);
            printf("\n %f quilometros ", km);
            printf("\n %f decimetros ", dm);
            printf("\n %f centimetros ", cm);
            printf("\n %f milimetros ", mm);
            printf("\n %f nanômetros", mmm);
            printf("\n %f picômetros", pm);
            printf("\n %f milhas náutica", nmi );
            printf("\n %f milhas", mi);
            printf("\n %f femara", fur);
            printf("\n %f fathom", ftm);
            printf("\n %f jarda", yd);
            printf("\n %f pés", ft);
            printf("\n %f polegadas", in);
            printf("\n %f gongli", gongli);
            printf("\n %f li", li);
            printf("\n %f zhang", zhang);
            printf("\n %f chi", chi);
            printf("\n %f cun", cun);
            printf("\n %f fen", fen);
            printf("\n %f lii", lii);
        main();
    }
int chamafuncao16()
    {
        float oparea, km, ha, a, m, dm, cm, mm, mmm, ac, milha, jd, ft, in, rd, qing, mu, chi, cun, gongli;
        printf("\n Digite 1 para metro quadrado");
        printf("\n Digite 2 para hectare ");
        printf("\n Digite 3 para are");
        printf("\n Digite 4 para quilometro quadrado");
        printf("\n Digite 5 para decimetro quadrado");
        printf("\n Digite 6 para centimetro quadrado");
        printf("\n Digite 7 para milimetro quadrado");
        printf("\n Digite 8 para micrometro quadro");
        printf("\n Digite 9 para acre");
        printf("\n Digite 10 para milha quadrada");
        printf("\n Digite 11 para jarda quadrada");
        printf("\n Digite 12 para pé quadrado");
        printf("\n Digite 13 para poplegada quadrada");
        printf("\n Digite 14 para vara quadrada");
        printf("\n Digite 15 para qing");
        printf("\n Digite 16 para mu");
        printf("\n Digite 17 para chi quadrado");
        printf("\n Digite 18 para cun quadrado");
        printf("\n Digite 19 para quilometro quadrado gongli \n");
        scanf("%f", &oparea);
    if(oparea==1)
    {
            printf("\n informe a quantidade de metro quadrado \n");
            scanf("%f", &m);



        }
    if(oparea==2)
    {
            printf("\n informe a quantidade de hectare \n");
            scanf("%f", &ha);
            m=ha*0.0001;

        }
    if(oparea==3)
    {
            printf("\n informe a quantidade de are \n");
            scanf("%f", &a);
            m=a*0.01;

        }
    if(oparea==4)
    {
            printf("\n informe a quantidade de quilometro quadrado \n");
            scanf("%f", &km);
            m=km*0.0000001;

        }
    if(oparea==5)
    {
            printf("\n informe a quantidade de decimetro quadrado \n");
            scanf("%f", &dm);
            m=dm*100;

        }
    if(oparea==6)
    {
            printf("\n informe a quantidade de centimetro quadrado \n");
            scanf("%f", &cm);
            m=cm*10000;


        }
    if(oparea==7)
    {
            printf("\n informe a quantidade de milimetro quadrado \n");
            scanf("%f", &mm);
            m=mm*1000000;

        }
    if(oparea==8)
    {
            printf("\n informe a quantidade de micrometro quadrado \n");
            scanf("%f", &mmm);
            m=mmm*100000*10000000;

        }
    if(oparea==9)
    {
            printf("\n informe a quantidade de acre \n");
            scanf("%f", &ac);
            m=ac*0.000247105407;


        }
    if(oparea==10)
    {
            printf("\n informe a quantidade de milha quadrado \n");
            scanf("%f", &milha);
            km=milha*0.000000386102159;
            m=km*0.0000001;

        }
    if(oparea==11)
    {
            printf("\n informe a quantidade de jarda quadrado \n");
            scanf("%f", &jd);
            m=jd*1.19599005;

        }
    if(oparea==12)
    {
            printf("\n informe a quantidade de pé quadrado \n");
            scanf("%f", &ft);
            m=ft*10.763910;

        }
    if(oparea==13)
    {
            printf("\n informe a quantidade de polegada quadrado \n");
            scanf("%f", &in);
            m=in*1550.0031;

        }
    if(oparea==14)
    {
            printf("\n informe a quantidade de vara quadrado \n");
            scanf("%f", &rd);
            m=rd*0.039536861;

    }
    if(oparea==15)
    {
            printf("\n informe a quantidade de qing \n");
            scanf("%f", &qing);
            m=qing*0.000015;

    }
    if(oparea==16)
    {
            printf("\n informe a quantidade de mu \n");
            scanf("%f", &mu);
            m=mu*0.0015;


        }
    if(oparea==17)
    {
            printf("\n informe a quantidade de chi \n");
            scanf("%f", &chi);
            m=chi*9;


    }
    if(oparea==18)
    {
            printf("\n informe a quantidade de cun \n");
            scanf("%f", &cun);
            m=cun*900;

    }
    if(oparea==19)
    {
            printf("\n informe a quantidade de quilometro quadrado gongli \n");
            scanf("%f", &gongli);
            m=gongli*0.000001;


    }
        km=m*1000000;
        m=km/1000000;
        ha=m*10000;
        a=m*100;
        dm=m*0.01;
        cm=m*0.0001;
        mm=m*0.0000001;
        mmm=m*0.0000000001;
        ac=m*4046.856;
        milha=m*2589988.11;
        jd=m*0.83612736;
        ft=m*0.09290304;
        in=m*0.00064516;
        rd=m*25.2928526;
        qing=m*66666.6667;
        mu=m*666.666667;
        chi=m*0.1111111111;
        cun=m*0.0011111111;
        gongli=m*1000000;

        printf("\n  %f metro quadrado", m);
        printf("\n  %f hectare ", ha);
        printf("\n  %f are", a);
        printf("\n  %f quilometro quadrado", km);
        printf("\n  %f decimetro quadrado", dm);
        printf("\n  %f centimetro quadrado", cm);
        printf("\n  %f milimetro quadrado", mm);
        printf("\n  %f micrometro quadro", mmm);
        printf("\n  %f acre", ac);
        printf("\n  %f milha quadrada", milha);
        printf("\n  %f jarda quadrada", jd);
        printf("\n  %f pé quadrado", ft);
        printf("\n  %f poplegada quadrada", in);
        printf("\n  %f vara quadrada", rd);
        printf("\n  %f qing", qing);
        printf("\n  %f mu", mu);
        printf("\n  %f quadrado", chi);
        printf("\n  %f cun quadrado", cun);
        printf("\n  %f quilometro quadrado gongli", gongli);
        main();
    }
int chamafuncao17()
    {
        float opvolume, m, dm, cm, mm, hl, l, dl, cl, ml, ft, in, yd, af;
        printf("\n Digite 1 para converter metro cubico ");
        printf("\n Digite 2 para converter decímetro cubico ");
        printf("\n Digite 3 para converter centímetro cubico ");
        printf("\n Digite 4 para converter milímetro cubico ");
        printf("\n Digite 5 para converter hectolitro ");
        printf("\n Digite 6 para converter litro  ");
        printf("\n Digite 7 para converter decilitro ");
        printf("\n Digite 8 para converter centilitro ");
        printf("\n Digite 9 para converter mililitro ");
        printf("\n Digite 10 para converter pé cubico ");
        printf("\n Digite 11 para converter polegada cubica ");
        printf("\n Digite 12 para converter jarda cubico ");
        printf("\n Digite 13 para converter acre cubico \n");
        scanf("%f", &opvolume);
        if(opvolume==1)
        {
            printf("\n Informe o tamanho em metros cubicos \n");
            scanf("%f", &m);


        }
        if(opvolume==2)
        {
            printf("\n Informe o tamanho em decimetros cubicos \n");
            scanf("%f", &dm);
            m=dm*1000;


        }
        if(opvolume==3)
        {
            printf("\n Informe o tamanho em centimetros cubicos \n");
            scanf("%f", &cm);
            m=cm*1000000;


        }
        if(opvolume==4)
        {
            printf("\n Informe o tamanho em milimetros cubicos \n");
            scanf("%f", &mm);
            m=mm*1000000000;


    }
        if(opvolume==5)
        {
            printf("\n Informe o tamanho em hectolitro \n");
            scanf("%f", &hl);
            m=hl*10;



    }
        if(opvolume==6)
        {
            printf("\n Informe o tamanho em litro \n");
            scanf("%f", &l);
            m=l/1000;


        }
        if(opvolume==7)
        {
            printf("\n Informe o tamanho em decilitro \n");
            scanf("%f", &dl);
            m=dl/10000;


        }
        if(opvolume==8)
        {
            printf("\n Informe o tamanho em centilitro \n");
            scanf("%f", &cl);
            m=cl/100000;


        }
        if(opvolume==9)
        {
            printf("\n Informe o tamanho em mililitro \n");
            scanf("%f", &ml);
            m=ml/1000000;



        }
        if(opvolume==10)
        {
            printf("\n Informe o tamanho em pé cubicos \n");
            scanf("%f", &ft);
            m=ft/35.3146667;

        }
        if(opvolume==11)
        {
            printf("\n Informe o tamanho em polegada cubica \n");
            scanf("%f", &in);
            m=in/61023.7441;


        }
        if(opvolume==12)
        {
            printf("\n Informe o tamanho em jarda cubica \n");
            scanf("%f", &yd);
            m=yd/1.30795062;


        }
        if(opvolume==13)
        {
            printf("\n Informe o tamanho em acre \n");
            scanf("%f", &af);
            m=af*1234;

        }

            l=m/0.001;
            m=l*0.001;
            dm=m*0.001;
            cm=m*0.000001;
            mm=m*0.000000001;
            hl=m*0.1;
            dl=m/0.0001;
            cl=m/0.00001;
            ml=m/0.000001;
            ft=m*35.3146667;
            in=m*61023.7441;
            yd=m*1.30795062;
            af=m/1234;

            printf("\n %f metro cubico ", m);
            printf("\n %f decímetro cubico ", dm);
            printf("\n %f centímetro cubico ",cm);
            printf("\n %f milímetro cubico ", mm);
            printf("\n %f hectolitro ", hl);
            printf("\n %f litro  ", l);
            printf("\n %f decilitro ", dl);
            printf("\n %f centilitro ", cl);
            printf("\n %f mililitro ", ml);
            printf("\n %f pé cubico ", ft);
            printf("\n %f polegada cubica ", in);
            printf("\n %f jarda cubico ", yd);
            printf("\n %f acre cubico \n", af);
        main();
    }
int chamafuncao18 ()
    {
        float op, b, kb, mb, gb, tb, pb;
        printf("\n 1 Para converte Byte ");
        printf("\n 2 Para converte Kilobyte ");
        printf("\n 3 Para converte Megabyte ");
        printf("\n 4 Para converte Gigabyte ");
        printf("\n 5 Para converte Terabyte ");
        printf("\n 6 Para converte Petabyte \n");
        scanf("%f", &op);
        if(op==1)
        {
            printf("\n Informe o numero de Bytes \n");
            scanf("%f", &b);
            kb=b*0.0009765625;
            mb=kb*0.0009765625;
            gb=mb*0.0009765625;
            tb=gb*0.0009765625;
            pb=tb*0.0009765625;

        }
        if(op==2)
        {
            printf("\n Informe o numero de kilobytes \n");
            scanf("%f", &kb);
            b=kb*1024;
            mb=kb*0.0009765625;
            gb=mb*0.0009765625;
            tb=gb*0.0009765625;
            pb=tb*0.0009765625;

        }
        if(op==3)
        {
            printf("\n Informe o numero de megabytes \n");
            scanf("%f", &mb);
            kb=mb*1024;
            b=kb*1024;
            gb=mb*0.0009765625;
            tb=gb*0.0009765625;
            pb=tb*0.0009765625;
        }
        if(op==4)
        {
            printf("\n Informe o numero de Gigabytes \n");
            scanf("%f", &gb);
            mb=gb*1024;
            kb=mb*1024;
            b=kb*1024;
            tb=gb*0.0009765625;
            pb=tb*0.0009765625;
        }
         if(op==5)
        {
            printf("\n Informe o numero de Terabytes \n");
            scanf("%f", &tb);
            gb=tb*1024;
            mb=gb*1024;
            kb=mb*1024;
            b=kb*1024;
            pb=tb*0.0009765625;
        }
         if(op==6)
        {
            printf("\n Informe o numero de Petabytes \n");
            scanf("%f", &pb);
            tb=pb*1024;
            gb=tb*1024;
            mb=gb*1024;
            kb=mb*1024;
            b=kb*1024;
        }
            printf("\n %f Bytes", b);
            printf("\n %f Kilobytes", kb);
            printf("\n %f Megabytes", mb);
            printf("\n %f Gigabytes", gb);
            printf("\n %f Terabytes", tb);
            printf("\n %f Petabytes", pb);
        main();
    }
int chamafuncao19()
    {
        float op, a, wk, d, h, min, s, ms, mms, ps;
        printf("\n Digite 1 para converte ano");
        printf("\n Digite 2 para converte semana");
        printf("\n Digite 3 para converte dia");
        printf("\n Digite 4 para converte hora");
        printf("\n Digite 5 para converte minuto");
        printf("\n Digite 6 para converte segundo");
        printf("\n Digite 7 para converte milisegundo");
        printf("\n Digite 8 para converte microsegundo");
        printf("\n Digite 9 para converte picosegundo \n");
        scanf("%f", &op);
        if(op==1)
        {
            printf("\n Informe a quantidade de anos \n");
            scanf("%f", &a);
            wk=a*52.1428571;

        }
        if(op==2)
        {
            printf("\n Informe a quantidade de semanas \n");
            scanf("%f", &wk);
            a=wk/52.1428571;

        }
        if(op==3)
        {
            printf("\n Informe a quantidade de dias \n");
            scanf("%f", &d);
            wk=d/7;

        }
        if(op==4)
        {
            printf("\n Informe a quantidade de horas \n");
            scanf("%f", &h);
            d=h/24;

        }
        if(op==5)
        {
            printf("\n Informe a quantidade de minutos \n");
            scanf("%f", &min);
            h=min/60;

        }
        if(op==6)
        {
            printf("\n Informe a quantidade segundos\n");
            scanf("%f", &s);
            min=s/60;

        }
        if(op==7)
        {
            printf("\n Informe a quantidade milisegundos\n");
            scanf("%f", &ms);
            s=ms/1000;

        }
        if(op==8)
        {
            printf("\n Informe a quantidade microsegundos\n");
            scanf("%f", &mms);
            ms=mms/1000;

        }
         if(op==9)
        {
            printf("\n Informe a quantidade picosegundos\n");
            scanf("%f", &ps);
            mms=ps/1000000;



        }

            a=wk/52.1428571;
            wk=a*52.1428571;
            d=wk*7;
            h=d*24;
            min=h*60;
            s=min*60;
            ms=s*1000;
            mms=ms*1000;
            ps=mms*1000000;
            printf("\n %f anos", a);
            printf("\n %f semanas", wk);
            printf("\n %f dias", d);
            printf("\n %f horas", h);
            printf("\n %f minutos", min);
            printf("\n %f segundos", s);
            printf("\n %f milisegundos", ms);
            printf("\n %f microsegundos", mms);
            printf("\n %f picosegundos", ps);


            main();
    }
int chamafuncao20()
    {
    setlocale(LC_ALL, "Portuguese");
    system("color 0a");
    int numeroprimo=0, maximotestado, testeprimodiv=0, recompensasemresto=0, quantosnumeros=0;
    printf("\n Informe até que numero devera achar primo \n");
    scanf("%d", &maximotestado);

    for(numeroprimo=2;numeroprimo<=maximotestado;numeroprimo++)
    {


        for(testeprimodiv=1;testeprimodiv<=numeroprimo;testeprimodiv++)
        {
            if(numeroprimo%testeprimodiv==0)
                {
                    recompensasemresto=recompensasemresto+1;
                }
            if(recompensasemresto>2&&testeprimodiv<numeroprimo)
            {
                testeprimodiv=numeroprimo;
            }

        }
        if(recompensasemresto==2)
        {
            printf("\n %d é um numero primo", numeroprimo);
            quantosnumeros=quantosnumeros+1;
        }
        recompensasemresto=0;

    }
    printf("\n No total são %d ", quantosnumeros);
    main();
}
int chamafuncao21()
{

    int op, rodagem=1;
    while(rodagem==1)
    {

        printf("\n\n0 Para voltar ao menu \n");
        printf("1 Para converte binário em decimal \n");
        printf("2 Para converte decimal em binário \n");
        scanf("%d", &op);
        system("cls");
        if(op==1)
        {
            int binario[30], decimal=0, quantos_bits, rodagem_for=0, aux=0, aux2;

            printf("Informe quantos Bits tem o numero \n");
            printf("Até 30 bits \n");
            scanf("%d", &quantos_bits);
            printf("Digite bit por bit \n");
            printf("Informe o numero em binário \n");
            for(rodagem_for=quantos_bits;rodagem_for>0;rodagem_for--)
            {

                scanf("%d", &binario[rodagem_for]);
                if(binario[rodagem_for]==1)
                {
                    aux2=rodagem_for-1;
                    aux=pow(2, aux2);
                    decimal=decimal+aux;
                }
            }

            printf("\n O resultado é %d", decimal);
        }
        if(op==2)
        {
            int numero_digitadoo, binarioo[30], vetoro;
            printf("Informe o numero de base decimal de no maximo 2147483647 \n");
            scanf("%d", &numero_digitadoo);
            for(vetoro=29;vetoro>=0;vetoro--)
            {
                if(numero_digitadoo %2==0 )
                {
                binarioo[vetoro]=0;
                }
                else
                {
                    binarioo[vetoro]=1;
                    numero_digitadoo=numero_digitadoo-1;
                }
                numero_digitadoo=numero_digitadoo/2;

            }
            printf("\n O resultado é ");
            for(vetoro=0;vetoro<30;vetoro++)
            {
            printf("%d", binarioo[vetoro]);
            }
        }
        else
        {
            rodagem=0;
        }

    }
    main();
}

