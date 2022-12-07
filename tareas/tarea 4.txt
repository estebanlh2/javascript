let mishapositivo = [5, 10, 15, 20]
let mishanegativo = [-6, -11, -16, -21]

function ayuda ( misha ) {
  return misha.map(misha => misha * -1);
}

let dimelo = ayuda(mishanegativo);

console.log(dimelo)
 
hacer que los positivos se vuelvan negativos y al contrario