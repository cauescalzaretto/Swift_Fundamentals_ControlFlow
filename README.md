# Swift Fundamentals ControlFlow

    /
    /: Playground - noun: a place where people can play
    
    
    
    import UIKit
    
    
    
    //==============================================================================
    
    // Estruturas de repetição - For / In
    
    //==============================================================================
    
    
    
    //for objetoDeLeitura in colecaoOuSequenciaASerUtilizada{
    
    // // Bloco de execução a ser repetido para todos os itens da sequência
    
    //}
    
    
    
    for semana in 1...7 {
    
    print(semana)
    
    }
    
    
    
    for meses in 1..<13 {
    
    print(meses)
    
    }
    
    
    
    let diasDaSemana = ["Seg","Ter","Qua","Qui","Sex","Sab","Dom"]
    
    for mostrarDia in diasDaSemana
    
    {
    
    print(mostrarDia)
    
    }
    
    
    
    
    
    //==============================================================================
    
    // Estruturas de repetição - While / Repeat While
    
    //==============================================================================
    
    
    
    //while condição {
    
    // //Bloco de execução
    
    // //Tratamento de parada da execução
    
    //}
    
    
    
    var contador = 100
    
    
    
    while contador > 0
    
    {
    
    print(contador)
    
    //tratamento de parada
    
    contador -= 1
    
    }
    
    
    
    //No While, se não colocarmos o tratamento de parada da execução, o processo entrará em
    
    // loop infinito.Esse processo pode gerar inconsistências na sua aplicação.
    
    
    
    var numeroPensado = 3
    
    var numeroComputador = Int()
    
    var tentativas = 0
    
    
    
    repeat
    
    {
    
    tentativas += 1
    
    numeroComputador = Int(arc4random_uniform(10))
    
    }
    
    while (numeroPensado != numeroComputador) && (tentativas <= 10)
    
    
    
    print("Você acertou em \(tentativas) vezes")



