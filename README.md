# DWDM21
Data Warehouse & Data Mining 2021

ขนิษฐา ภูโสภา 623021042-5

**Group name Natasha Romanoff**

1 จิตติยา ศิริธรรมจักร 623021043-3

2 จุฑากาญจน์ ชิงจันทร์ 623020514-5

3 ขนิษฐา ภูโสภา 623021042-5

4 ชนกานต์ พูลผล 623021046-7

5 ฐิติวัฒน์ จันทรเสนา 623021047-5

**สารบัญเนื้อหา**

วิชา Data Mining and Data Warehouse

* บทที่ 1  Introduction  https://github.com/khanittha-phusopha/DWDM21/blob/main/%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%9A%E0%B9%89%E0%B8%B2%E0%B8%9901.pdf ประกอบด้วยหัวข้อ ดังนี้

   * ทำไมต้องมีการทำเหมืองข้อมูล (Why Data Mining?)

   * อะไรคือเหมืองข้อมูล (What Is Data Mining?)

   * มุมมองหลายมิติของเหมืองข้อมูล (A Multi-Dimensional View of Data Mining)

   * สามารถขุดเเหมืองข้อมูลที่ไหนได้บ้าง (What Kinds of Data Can Be Mined?)

   * รูปแบบหรือทิศทางของข้อมูล (What Kinds of Patterns Can Be Mined?)

   * ใช้เทคโนโลยีประเภทใด? (What Kinds of Technologies Are Used?)

   * แอพพลิเคชั่นเป้าหมาย(What Kinds of Applications Are Targeted?)

   * ความสำคัญในการทำเหมือง(Major Issues in Data Mining)

   * ประวัติความเป็นมา(A Brief History of Data Mining and Data Mining Society)

   * สรุป (Summary)

* บทที่ 2 Getting to Know Your Data ประกอบด้วยหัวข้อ ดังนี้ มี 4 ไฟล์ 

   * Basic Python https://github.com/khanittha-phusopha/DWDM21/blob/main/Data101(Chapter2).ipynb
   
      * Casting (int(),str())
    
      * Data Structure (list(),list,วิธีการสร้าง,การชี้ค่า,Loop,Condition,Function)
    
    * Plot Data  https://github.com/khanittha-phusopha/DWDM21/blob/main/Data102(Chapter2).ipynb
    
      * Besic Data
 
      * การตรวจสอบตารางข้อมูลโดยใช้ .head()&.tail()
 
      * Boxplot
 
      * Time Series Plot
 
    * Visualizetion https://github.com/khanittha-phusopha/DWDM21/blob/main/Data_Visualizetion.ipynb
    
      * Scatter plot (กำหนดขนาด,กำหนดสี,marker,alpha)
      
      * Plot 
     
      * Bar chart (grouped,stacked)
      
      * Histogram
      
    * Distance Numpy https://github.com/khanittha-phusopha/DWDM21/blob/main/Distance_numply.ipynb
   
      * Numpy Array (Indexing & Slicing, Useful functions,วนลูป,Quiz กลุ่ม)
     
      * Distance Matrix ( Euclidean Distance (L2-norm),Distance function,Manhattan Distance (L1-norm) )
      
* บทที่3 https://github.com/khanittha-phusopha/DWDM21/blob/main/Data%20Preprocessing(Chapter%203).ipynb  มีหัวข้อดังนี้

     * Meta Data 
     * การจัดการข้อมูลในตารางก่อนนำไปวิเคราะห์
          
       * ชี้ข้อมูลในตาราง (ชี้แบบธรรมดา ใช้ [ชื่อ column][index],ชี้แบบ .iloc[] (มองข้อมูลเป็น metrix))

       *  Missing Value
       
          * วิธีกำจัด Missing
          
          * Quiz3 หาว่าการทำ dropna() ทำให้ข้อมูลหายไปกี่ %
          
          * Handle Missing Value 1.5 (ลบค่า Missing เฉพาะใน column ที่เราสนใจ)
          
          * Quiz 3.1 ให้ หาว่า การทำ .dropna() แบบเลือก drop ทำให้ข้อมูลหายกี่ %
        
             * Handle Missing Value 2
             
             * Handle Missing Value 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
             
             * Handling Missing Value 4 (แทนด้วยค่ากลาง)
             
             * Handling Missing Value 5 (แทนด้วย column ใกล้เคียง)
           
       * PANDA
      
          * Select data by values [PD]
        
          * เราใช้ & (and) และ | (or) ในการรวม list ของ boolean
         
* บทที่4 https://github.com/khanittha-phusopha/DWDM21/blob/main/%E0%B8%9A%E0%B8%974.pdf มีหัวข้อดังนี้

  * Basic Data Warehouse
        
      * อะไรคือคลังข้อมูล
      * วัตถุประสงค์
      * การบูรณาการ

  * Data Cube and OLAP

     * OLTP vs. OLAP
     * Data Cubes
     * Conceptual Modeling of Data Warehouse
    
  * การออกแบบ และการใช้งานคลังข้อมูล 
  * ความสำคัญของคลังข้อมูล 
    
* บทที่5 Association_Rules https://github.com/khanittha-phusopha/DWDM21/blob/main/Chapter6_Association_Rules.ipynb มีหัวข้อดังนี้

  * ความหมาย
    * ลบ records ที่ถูก cancel ออกไป
  * Basic concepts
    * มีประเทศสาขาของ supermarket นี้ทั้งหมดกี่ประเทศ
    * Plot graph of Itemsets
    * เตรียม Data สำหรับ (Fequence Pattern) Association Rule

  * Efficient Pattern Mining Methods
    * Apriori
    
* บทที่6 Classification มีหัวข้อดังนี้

  * Desition Tree https://github.com/khanittha-phusopha/DWDM21/blob/main/Chapter7_Classification_(Decisoin_Tree).ipynb
    * Load Data
    * Trian Model
    * plot tree
    * Evaluation
    * Random
    * Advanced Tree
    * HW

  * KNN https://github.com/khanittha-phusopha/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb
    * Load data
    * Split Data
    * Train Model
    * Retrain & Evaluate
    * Neural Network
    
  * Evaluation https://github.com/khanittha-phusopha/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb
    * Split Data หรือ แบ่ง Data
    * สร้าง Model ทำนาย
    * Evaluation
    
* บทที่7 Clustering https://github.com/khanittha-phusopha/DWDM21/blob/main/Chap8_Clustering.ipynb มีหัวข้อดังนี้
  
  * K-means
    * Generate Data
    
    * Explore data
    * Clustering
        * Import
        * Define
        * Fit-Predict

     * Example Application(Color Quantization)
        * นับจำนวนสี
        * ใช้ centorid เป็นตัวแทนของสี
   
  * สไลด์ประกอบการเรียน https://github.com/khanittha-phusopha/DWDM21/blob/main/Chapter8.pdf

* Project กลุ่ม Natasha https://github.com/khanittha-phusopha/DWDM21/blob/main/Project.ipynb

  * สไลด์นำเสนอ https://github.com/khanittha-phusopha/DWDM21/blob/main/Project.pdf
    
    
    
    
    
