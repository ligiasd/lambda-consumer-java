## lambda-consumer-java  

 Criando funções que recebem funções como argumento:  foreach(Consumer)
 
 Consumer  
• https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html  
• Nota: ao contrário das outras interfaces funcionais, no caso do Consumer, é esperado ele possa gerar efeitos colaterais.  

public interface Consumer<T> {  
void accept(T t);  
}  

Operações intermediárias  
• filter  
• map  
• flatmap  
• peek  
• distinct  
• sorted  
• skip  
• limit (*)  
* short-circuit  


Operações terminais  
• forEach  
• forEachOrdered  
• toArray  
• reduce  
• collect  
• min  
• max  
• count  
• anyMatch (*)  
• allMatch (*)  
• noneMatch (*)  
• findFirst (*)  
• findAny (*)  
* short-circuit  


