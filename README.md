# csPortfolio

* WebPage [here]()
* Lightning [here]()
* Lighting JS [here]()
* Chemotaxis [here](https://cridlebaughg.github.io/chemotaxis4/)

```Java
void layer5create(){
  for(int i = (int)(Math.random() * 40); i < 50; i++){
    ethans.add(new Ethan(ethanimg,(int)(Math.random() * width),(int)(Math.random()*height)));
  }
  for(int i = ethans.size() - 1; i > -1; i--){
    if(ethans.get(i).y < foreground[ethans.get(i).x]){
      ethans.remove(i);
    }
  }
}
```
