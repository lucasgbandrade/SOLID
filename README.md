# Princípios S.O.L.I.D.

Os cinco princípios que serão apresentados aqui, são conhecidos como princípios SOLID, que é um acronimo definido pela letra inicial de cada princípio.
Esses princípios não visam apenas resolver um problema, mas também garantir que a solução possa evoluir e ser mantida.


## **S** - Princípio da Responsabilidade Única (**S**ingle Responsibility Principle)

Esse princípio indica que toda classe deve ter uma única responsábilidade.

Exemplo de violação do principio de responsabilidade única.
```c#

  public class Class1
  {
      public int Property1 { get; set; }
      public string Property2 { get; set; }
      public string Property3 { get; set; }
      
      public int Salvar()
      {
          if(String.IsNullOrEmprty(Property2)
            throw new Exception("");
            
          return 0;
      }
      
      public bool Deletar()
      {
      
      }
      
  }
```

## **O** - Princípio Aberto/Fechado (**O**pen/Closed Principle)


## **L** - Princípio da Subistituição de Liskov (**L**iskov Substitution Principle)

## **I** - Princípio da Segregação de Interfaces (**I**nterface Segregation Principle)

## **D** - Princípio da Inversão de Dependência (**D**ependency Inversion Priciple)
