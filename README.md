func loveCalculator() {
  let lovescore =  Int.random(in: 0...100)

  switch lovescore {
  case 81...100:
    print("yall love ye")
    case 41..<81:
    print("Sneaky and meteos")
    case ...40:
    print("you not having no one nigg"a)
      
  default:
      fatalError("Unsupported")
  }
  
  if lovescore > 80 {
      print("yall love ye")
     } else if lovescore > 40 { 
          print("sneaky and meteos")}
          else {print("you alone")}
  }
loveCalculator()
