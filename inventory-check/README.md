# Esercizio 1

* Dato un array di prodotti e uno di quantità, stampa se il prodotto è esaurito o se le scorte sono basse.

## Ragionamento

* dichiarare array prodotti;
* dichiarare array quantità;
* dichiarare una soglia per le scorte basse (lowStockThreshold);
* utilizzare un ciclo for per iterare su entrambi gli array contemporaneamente;
  * se la quantità del prodotto è 0, stampare che il prodotto è esaurito;
  * altrimenti se la quantità è minore della soglia (lowStockThreshold), stampare che le scorte sono basse;
  * altrimenti stampare che il prodotto è disponibile.

---

## Exercise 1

* Given an array of products and one of quantities, print if the product is out of stock or if the stock is low.

## Reasoning

* declare an array for products;
* declare an array for quantities;
* declare a threshold for low stock (lowStockThreshold);
* use a for loop to iterate through both arrays simultaneously;
  * if the product quantity is 0, print that the product is out of stock;
  * else if the quantity is lower than the threshold (lowStockThreshold), print that the stock is low;
  * otherwise, print that the product is in stock.
