# Padrão de Projeto Factory em Java

 Uma fábrica (factory) é simplesmente um objeto que retorna outro objeto a partir de alguma chamada de método, geralmente associado à criação de novos objetos.

 Neste problema, você tem uma interface chamada Food. Existem duas classes, Pizza e Cake, que implementam a interface Food. Ambas contêm um método chamado getType().

 A função principal, na classe Main, cria uma instância da classe FoodFactory. A classe FoodFactory contém um método chamado getFood(String) que retorna uma nova instância de Pizza ou Cake, dependendo do parâmetro recebido.
