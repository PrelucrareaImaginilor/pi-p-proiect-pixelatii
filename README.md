
## State-of-the-art research


|Nr. |Autori / An | Titlu articol / proiect | Aplicație / Domeniu | Tehnologii utilizate | Metodologie / Abordare| Rezultate | Limitări | Comentarii suplimentare |
|--------------|------------|-------------------|---|---|---|---|---|---|
1.|	Abhishek Das, Japsimar Singh Wahi, Mansi Anand, Yugant Rana / *2022*	|	**Multi-Image Steganography Using Deep Neural Networks**	|	Steganografie utilizand retele neuronale 	| Retele neuronale convolutionale  | Exista 2 retele neuronale, una pentru codificare si alta pentru decodificare  | Ascunderea si recuperarea mai multor imagini secrete, dintr-o singura imagine de acoperire | Maxim 3 imagini, pierderea de date creste odata cu numarul de imagini |
2.|Varsha Kishore , Xiangyu Chen , Yan Wang, Boyi Li & Kilian Weinberger / *2022*		|**FIXED NEURAL NETWORK STEGANOGRAPHY: TRAIN THE IMAGES, NOT THE NETWORK**|	Anonimizare a feței folosind FNNS|Fixed Neural Network Steganography|Autorii propun o metoda de steganografie prin care nu se pierd date|Generarea de imegini folosind gradientul din pierderea între ieșirea decoder-ului și mesajul secret|Este dependent de domeniul din care fac parte datele.|
3.|Kevin A. Zhang, Alfredo Cuesta-Infante, Lei Xu, Kalyan Veeramachaneni / *2019*|**SteganoGAN: High Capacity Image Steganography with GANs**|Steganografie folosind retele neuronale| Retele generative adversiale (GANs)|Autorii propun o noua utilizare a GAN-urilor in domeniul steganografiei.|Devine posibila codificarea si decodificarea imaginilor folosind GANs, evitand tool-urile de detectie traditionale.|Consum ridicat de resurse, distorsiunile cresc odata ce se depasesc 4.4 biti per pixel.|Aceasta este una dintre primele lucrari ce propune o tehnica de ML pentru steganografie. Urmatoarele studii cauta sa imbunatateasca aceasta|
4.|Shikhar Khandelwal, Shyamansh Sharma, Mr. Arvind Kumar / *2024*|**Data Transfer Security with Steganography**|Aplicatie de mesagerie folosind steganografia.|Aplicatii de editare foto, algoritmi pentru hashing.|Mesajele sunt incorporate in imagini prin steganografie traditionala.|Folosirea imaginilor steganografice ca metoda de encriptie a mesajelor uzuale.|Capacitatea limitata datorita metodei de steganografie folosite
5.|Guobiao Li, Sheng Li, Zhenxing Qian, Xinpeng Zhang / *2024*|**Cover-separable Fixed Neural Network Steganography via Deep Generative Models**|Hiding Multiple Images for Different Receivers|Steganographic Perturbation Search (SPS) Fixed Neural Netowrk Steganography - FNNS, Deep Generative Models|Se foloseste Stable Diffusion pentru a crea o imagine de acoperire, dupa care SPS optimizeaza o perturbare minima care este adaugata imaginii de acoperire. Astfel, in aceeasi imagine pot exista informatii pentru persoane diferite.|Rezultatele experimentale demonstrează superioritatea metodei propuse față de schemele FNNS existente. De asemenea, metoda este adaptata pentru a fi rezistenta la compresie JPEG si poate ascunde multiple imagini pentru receptori diferiti.|Din cauza resurselor de calcul limitate, mtoda este antrenata să ascundă până la patru imagini secrete. De asemenea, este vulnerabila la compresii JPEG mai agresive.|

![PIP-STEGA-v1 drawio](https://github.com/user-attachments/assets/005c1c2c-2594-4fbe-9a49-a32bc51c7f7c)
