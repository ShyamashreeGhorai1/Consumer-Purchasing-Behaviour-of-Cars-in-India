
💭 Feynn Labs Internship 💭



🚓 <b> Consumer Purchasing Behaviour of Cars in India </b> 🚕



![download](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/d251d694-91a0-4ef5-95f4-ab7a184b5369)


 🌱 Introduction:

       The automobile industry of India is one of the largest in the world, contributing 7.1% to
       the Gross Domestic Product (GDP).Nowadays purchasing a car is the first choice of any 
       individual when he/she climbed up the ladder of his income. There are many factors that may
       affect the purchasing rate of the cars. Objective of this study is to analyse the consumer
       behaviour for purchasing cars in India to improve the car sales from the dealer.


 ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/8b1b2a04-c883-4529-9ae3-4f30b04e3d1f)
    
🌱 Dataset and Features:

      This study conduct an analysis on “Indian Consumers Cars Purchasing Behaviour” dataset. There
      are 13 features in the dataset with 99 observations. Features of the dataset are: 1) Age 
      2) Profession 3) Marrital Status 4) Education 5) No of Dependents 6) Personal Loan 7) House Loan 
      8) Wife Working 9) Salary 10) Wife Salary 11) Total Salary 12) Make 13) Price. 
      
🌱 Data Cleaning:

     There is no missing and duplicate value in the dataset. One inconsistent value presents in the
     dataset which removed from the dataset using drop () method. There are outliers in the dataset 
     and removed possible outliers from the dataset.

 🌱 Data Analysis:

   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/dc368163-0f26-4aad-bdba-830694124961)
   
   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/280c2aad-311a-43db-9b56-6ed0ea29028c)

    Observation:
      • Major part of consumers are salaried and married. Also do not have any personal loan and house loan.
      • Consumers with post graduate are more visible than graduate in the dataset.

   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/b0a30950-7fe0-4972-bb6b-4700445a635c)

     Observation:
       • Major part of consumers purchased car with brand baleno, suv and creata.

   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/2d72168b-2cc0-4e1c-bb75-9cfad455bbfb)

      Observation:
        • Correlation found between:  price and no of dependents, salary and total salary, 
          salary and age, price and total salary, wife salary and total salary, wife salary and price.

🌱 Data Pre-processing:

      There are categorical features in the dataset. So, converted categorical features into numerical
      value using replace () method. After this standardized the dataset using preprocessing.scale () technique.

 🌱 Segmantation:

      PCA has been applied on the dataset. 

   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/18197ba0-328d-4dae-9d6f-8cee4fe66dbc)

       Interpretation:

           • The column PC1 indicates how the first principal component is composed of the original 
           variables. For the first principal component total Salary, Wife Salary and Age are important
           variables. For the second principal component Personal loan, House Loan and No of Dependents
           are important variables. For the third principal component Wife Working and Salary are 
           important variables.
   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/d452fcb5-95d4-42a8-b45f-ce3535062cd8)

       Interpretation:

          • From the above figure, we can say that Personal loan, House Loan, No of Dependents are quite
           unique. We can be interpreted as: attributes Age, Marrital Status, Salary point in the same 
           direction, attributes Total Salary, Make, Education, Profession point in the same direction 
           and Price, Wife Salary, Wife Working point in the same direction.

   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/39cd9f8b-cc47-48de-b183-836934d8200a)

       Observation:

          • From Elbow method, we observe an elbow at k = 4.

   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/ce40e5a5-a055-4936-b4f8-6463dd4facce)

       Observation:

          • From Dendrogram, we observe 4 clusters. 


   🌱 Cluster Visualization:
    
   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/9202865a-5c38-486d-8aad-8c0f202b691a)

   ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/ab06a52a-1862-4642-a8d5-f2bea178b0dd)

     Observation:

          • Major part of the customers belongs to cluster 0 and cluster 2.

   🌱 Selecting Target Segment:

         Cluster Interpretation:

  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/75fb1502-8555-4e0a-bf11-6d016d677efd)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/8be312b0-9545-4a63-99f3-eb24775c72f0)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/2b30b539-1ac6-4ddf-902e-d10b61a89289)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/eaf05b49-fb7c-4359-8733-41f08b40eada)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/3f71575b-76c5-4230-aba0-f9269f50940b)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/e6aa00bb-063d-4531-aa65-3770432f5a67)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/b8859917-4e29-4280-9f7b-b667813b823e)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/fc17a4a5-9b21-4730-8480-759003c62400)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/ab2bb4bd-4a34-45da-b160-9af7b8619ba1)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/22fd45d7-3590-4d78-9846-2a80490e6c45)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/961aa476-dd8e-48b7-8a34-9aaa082613ac)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/104404b8-3af8-4924-b8d9-811eeae65f28)
  ![image](https://github.com/ShyamashreeGhorai1/Consumer-Purchasing-Behaviour-of-Cars-in-India/assets/131132617/1f21d7a9-2f39-4621-8e54-db3e7e595f87)

    
 
