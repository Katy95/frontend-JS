    var score = 95;
    score = parseInt(score/10);
    switch(score){
      case 10:
      case 9: //因为10时没有break，所以会执行9的case
        console.log('A');
        break;
      case 8:
        console.log('B');
        break;
      case 7:
        console.log('C');
        break;
      case 6:
        console.log('D');
        break;
      defalut:
        console.log('E');
        break;
     }
