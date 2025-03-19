class tipoHeroi {
    constructor(raca){
        this.raca = raca
    // Define classe e poder de acordo com a raça
        if (raca === "mago") {
            this.poder = "magia";
        } else if (raca === "guerreiro") {
            this.poder = "força";
        } else if (raca === "monge") {
            this.poder = "artes marciais";
        } else if (raca === "ninja") {
            this.poder = "shuriken";
        }
    }
            toString(){
                return (`Um herói ${this.raca} com poder de ${this.poder}`)
            }
} 

let mago = new tipoHeroi('mago');
console.log(mago.toString());

