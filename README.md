# RF-localization
Publication:
https://esveske.github.io/pdf/2019/PS78-Zb2019_I-PFE-MNAS.pdf
           
English        
          
           The goal of this project is to find the unknown position of the transmitter in space by analyzing radio wave characteristics at the receiver side.
           The apparatus consisted  of one transmitter with an emission frequency of 433MHz and 3-5 receiving antennas. Average values of voltage induced 
           by the electromagnetic field of the transmitter were measured. Linear dependence of receiver power from voltage squared has been noted, which 
           gave us the possibility to use all the methods that analyse power characteristics. Measures were held on a conducting metal table due to which, by the 
           method of image charges, there was a superposition of emitted waves from the original transmitter and its image. In this paper, 4 different methods
           were compared: Trilateration, Gradient Descent, Gauss-Newton method (GNA) and Levenberg-Marquardt (LM) algorithm. All methods except trilateration
           are optimization algorithms and their goal is to minimize the residual function, represented by a module of difference of measured voltage vectors.
           Analyzing results gained by simulation of the whole system the influence of the conducted table has been determined, as well as the height of the 
           antennas at which power losses were minimal. The average error for all algorithms in cases with 3, 4 and 5 antennas were analyzed. The error was 
           found to decrease as the number of antennas increased. The average error using three antennas and the LM algorithm was 15cm, while with 5 antennas 6cm.
           Comparing algorithms it is concluded that the LM algorithm was the best, and that trilateration (error 8cm) produced better results than GNA or Gradient
           Descent method (11cm and 14cm, respectively).
         
Srpski       
         
           Cilj rada je određivanje lokacije predajnika ispitivanjem karakteristika radio talasa koji stižu do prijemnika. Aparatura se sastoji od predajne 
           antene emisione frekvencije 433 MHz i 3-5 prijemnih antena. Merene su srednje vrednosti napona indukovanih na antenama usled električnog polja 
           predajnika. Uočena je linearna zavisnost snage prijemnika od kvadrata napona, čime su ova merenja mogla biti obrađivana svim metodama vezanim za 
           snagu. Merenja su vršena na provodnom metalnom stolu usled čega je, prema teoremi likova, dolazilo do superpozicije talasa emitovanih od strane 
           predajnika i njegovog lika sa druge strane stola. Upoređena su četiri metoda: trilateracija, metoda opadajućeg gradijenta, Gaus-Njutnova metoda (GNA)
           i Levenberg-Markvarov (LM) algoritam. Svi oni su, osim trilateracije, optimizacioni algoritmi, i cilj im je da minimizuju funkciju greške,
           predstavljenu kao modul razlike vektora izmerenih napona. Analizom rezultata simulacije sistema utvrđen je uticaj provodnog stola, kao i visina 
           antena kada je opadanje snage u toku udaljavanja najmanje. Analizirana je prosečna greška u slučajevima sa 3, 4 i 5 antena. Utvrđeno je da se greška
           pri korišćenju svih algoritama smanjuje pri povećanju broja antena. Prosečna greška u slučaju tri antene i LM algoritma iznosila je 15 cm, a sa 5 
           antena 6 cm. Poređenjem algoritama zaključuje se da je LM algoritam najbolji, a da se trilateracijom (greška 8 cm) dobijaju bolji rezultati nego GNA
           ili opadajućim gradijentom (11 cm i 14 cm, respektivno).

![lokalizacija-0 3](https://user-images.githubusercontent.com/57879705/140623730-2af34905-eb15-45f3-89fa-2968431c9515.jpg)
