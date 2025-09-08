# CSOPORT GITHUB LINK
[CSOPORT LINK](https://drive.google.com/drive/folders/13AGHxSVfgTrBsZo19crcuXa43jSNrOhQ?usp=sharing)

# Bemutatkozás

## Rólam
Üdvözöllek! A nevem **Peti**, mérnökként dolgozom, és szenvedélyem a technológia, a hangtechnika és az oktatás.  
Fontos számomra a precizitás, a szakmai fejlődés, valamint az, hogy tudásomat átadhassam másoknak.

## Foglalkozás
- Mérnöki háttérrel rendelkezem
- Hangtechnikai és rendezvényes projektekben aktívan részt veszek
- Oktatóként dolgozom, ahol a diákjaimnak nemcsak műszaki, hanem projektmenedzsment szemléletet is átadok

## Érdeklődési körök
- **Hangtechnika**: hangrendszerek tervezése és üzemeltetése
- **Informatika és távközlés**: hálózatok, API-fejlesztés, szoftverfejlesztés
- **Oktatás**: diákok támogatása projektmunkában és szakmai fejlődésben
- **Hobbi**: DJ-zés, fotózás, videózás, streamelés

## Értékek, amiket képviselek
- Pontosság és megbízhatóság  
- Rendszerszemlélet és hatékony problémamegoldás  
- Tudásmegosztás és utánpótlás-nevelés  

## Elérhetőség
- 📧 Email: info@sprendezveny.hu  
- 📍 Lakhely: Miskolc környéke, Magyarország  

---
*Köszönöm, hogy benéztél!* 

--- 


|o1|o2|o3|
|--|--|--|
|Low|Key|Nah|

1. afasfdafdsg
2. asdgdsagdsag
3. asdgsadgdsag
4. asdgsadg
5. asdgsadg

--- 

Youtube pingelés: 

<img width="543" height="285" alt="image" src="https://github.com/user-attachments/assets/dc3c5b89-8297-4b8a-9c61-139e44741656" />

---

CODE:

```
//Initialize the array that will hold the primes
var primeArray = [];
/*Write a function that checks for primeness and
pushes those values to the array*/
function PrimeCheck(candidate){
  isPrime = true;
  for(var i = 2; i < candidate && isPrime; i++){
    if(candidate%i === 0){
      isPrime = false;
    } else {
      isPrime = true;
    }
  }
  if(isPrime){
    primeArray.push(candidate);
  }
  return primeArray;
}
/*Write the code that runs the above until the
length of the array equals the number of primes
desired*/

var numPrimes = prompt("How many primes?");

//Display the finished array of primes

//for loop starting at 2 as that is the lowest prime number keep going until the array is as long as we requested
for (var i = 2; primeArray.length < numPrimes; i++) {   
    PrimeCheck(i); //
}
console.log(primeArray);
```
