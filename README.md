# Papeleria
void main() {
  
  Map<int,String> smart =
  {
    101: "pan bimbo",
    102: "galon  leche",
    103: "papitas",
  };//mapa smart
  
  print(smart);
  
  for(int codigo in smart.keys){
    print(codigo);
  }//fin for codigo
  
  for(String articulos in smart.values){
    print(articulos);
  }//fin for codigo
  
   Map<String,double> papeleria =
   {
   204: "cuaderno", 
   };
  print(papeleria);
} 
