# DWDM21
### :point_right: Data Warehouse & Data Mining 2021

### :point_right: นางสาววนิศรา จงใจ 623021054-8

### :point_right: Group Name : Numberone

### รายชื่อสมาชิก

| รหัสนักศึกษา | ชื่อ-สกุล | สาขา |
| ----------- | ----------- |----------- |
| 623020527-6 | นางสาวเบญญาภา ระภูเขียว | SC-SI |
| 623020765-0 | นายศิริวัฒน์ ภูลำสัตย์ | SC-SI |
| 623021049-1 | นายธนิก พิมภิบาล | SC-SI |
| **623021054-8** | **นางสาววนิศรา จงใจ** | **SC-SI** |
| 623021055-6 | นายวิฆเนศ เกียรติเกษมสุข | SC-SI |

---

# สารบัญเนื้อหา

รายวิชา Data Warehouse & Data Mining เป็นวิชาที่เกี่ยวกับ Data ว่ามีกระบวนการอะไรบ้าง หลังจากถูกเก็บไว้ใน Data Base เพื่อนนำมาสกัดเป็นความรู้ นำไปใช้ประโยชน์ , ใช้ในการวางแผน ซึ่งก็คือ Data Mining 

## บทที่1 
* [introduction](https://github.com/Jaomiew/DWDM21/blob/main/HW1.)
  * นิยามของ Data Mining
  * ทำไมจึงต้องมี Data Mining
  * ขั้นตอนการสกัดสารสนเทศ
  * เทคนิคในการทำ Data Mining 

## บทที่ 2 
#### Lecture
  * [สรุปการบ้านคาบ 1 Know your data](https://github.com/Jaomiew/DWDM21/blob/main/HW2.ipynb)
    * ประเภทข้อมูล
    * ลักษณะสำคัญของข้อมูล
#### Googlecolab 
 * know your data ประกอบไปด้วย 3 ส่วยย่อย
   * [Basic Python](https://github.com/Jaomiew/DWDM21/blob/main/Data101(Chapter2).ipynb)
      * Casting การเปลี่ยนชนิดของตัวเเปร
      * Data Structure โครงสร้างของข้อมูล
      * Loop การวนซ้ำ
      * Condition เงื่อนไข
      * Function
      * [Mount G Drive](https://github.com/Jaomiew/DWDM21/blob/main/Data102_(Chapter2).ipynb)
         * head() , tail()
         * Boxplot
         * Time Series Plot
   * [Data Visualization](https://github.com/Jaomiew/DWDM21/blob/main/Data_Visualization.ipynb)
      * Scatter plot
      * Plot
      * Bar chart
         * Grouped Barchart
         * Stacked Barchart
      * Histogram  
   * [Distance Numpy](https://github.com/Jaomiew/DWDM21/blob/main/Distance_Numpy.ipynb)
      * Numpy Array
         * สร้าง numpy array (matrix) 
         * สร้าง matrix เริ่มต้น (zeros, ones)
         * สร้าง matrix random
              * matrix properties
         * matrix properties
         * Useful functions
         * วนลูปเอง
              * summation
      * Distance Matrix
         * Euclidean Distance (L2-norm)
         * Distance function
         * Manhattan Distance (L1-norm)
      * Distance of Binary Value
  
## บทที่ 3 
#### Lecture
  * [สรุป Chapter 3 Handling Missing](https://github.com/Jaomiew/DWDM21/blob/main/Chapter_3_(Handling_Missing).ipynb)
#### Googlecolab
  * [Data Preprocessing](https://github.com/Jaomiew/DWDM21/blob/main/Data_Preprocessing_(Chapter3).ipynb)
      * ชี้ข้อมูลในตาราง 
         * ชี้แบบธรรมดา 
         * ชี้แบบ .iloc
      * Missing Values
      * Handling Missing Value
         * วิธีที่ 1 (ลบค่า missing ออกไป) 
         * วิธีที่ 1.5 (ลบค่า missing เฉพาะใน column ที่เราสนใจ)
         * วิธีที่ 2 (แทนด้วย class ใหม่ (unknown)
         * วิธีที่ 3 (แทนด้วย class ใหม่ (ค่าที่เหมาะสม)
         * วิธีที่ 4 (แทนด้วยค่ากลาง)
         * วิธีที่ 5 (แทนด้วย ค่ากลางของ samples ใน class เดียวกัน)
      * Select data by values [PD]
      * Outlier
      * การรวมตาราง Data Integration
      * Grop by (pandas) 
  
 ## บทที่ 4 
  * [ Data Warehousing and On-line Anaalytical Processing](https://github.com/Jaomiew/DWDM21/blob/main/Chapter4-New.pdf) ประกอบไปด้วย
     * Data Warehouse : Basic concepts
       * คลังข้อมูลอะไร
       * วัตถุประสงค์
       * การบูรณาการ
     * Data Warehouse Mining : Data Cube and OLAP
       * OLTP vs. OLAP
       * Data Cubes
       * Conceptual Modeling of Data Warehouse
     * Data Warehouse Disng and Usage
     * Data Warehouse Implementation

## บทที่ 5 
#### Lecture
  * [สรุป Chapter 6](https://github.com/Jaomiew/DWDM21/blob/main/Chapter-6-New%20(1).pdf)
    * Besic Concepts
      * Plot graph of Itemsets
      * การแก้ไขคอลัมน์ข้อมูล
      * Frequence Itemsets to Association Rule
    * Efficient Pattern Mining Methods
      * Apriori
      * Support
#### Googlecolab
  * [Association Rules](https://github.com/Jaomiew/DWDM21/blob/main/Chapeter6_Association_Rules.ipynb)
    * Besic Concepts
       * K-itemsets
       * Plot graph of Itemsets
       * Frequence Itemsets to Association Rule
    * Efficient Pattern Mining Methods
       * Apriori
       * Support
 
## บทที่ 6 
 * ประกอบไปด้วย 3 ส่วยย่อย คือ
   * [Desition Tree](https://github.com/Jaomiew/DWDM21/blob/main/Chapter7_Classification_(Decision_Tree).ipynb)
      * Train Model
         * Import
         * Define
         * Train
      * plot tree
      * Evaluation
      * Advanced Tree
      * TEST
   * [KNN](https://github.com/Jaomiew/DWDM21/blob/main/Chap7_Classification_(KNN_NN).ipynb)
       * Split Data
       * Train Model
       * Retrain & Evaluate
       * Neural Network
   * [Evaluation](https://github.com/Jaomiew/DWDM21/blob/main/Chap7_Classification_(Evaluation).ipynb)
       * Split Data
       * สร้าง Model ทำนาย
       * Evaluation

## บทที่ 7 
#### Lecture
  * [สรุป Classifier](https://github.com/Jaomiew/DWDM21/blob/main/Chapter_8_Classifier.ipynb)
  * [Homeworks InfoD](https://github.com/Jaomiew/DWDM21/blob/main/Homeworks_InfoD.ipynb)
#### Googlecolab
  * [Clustering](https://github.com/Jaomiew/DWDM21/blob/main/Chap8_Clustering.ipynb)
     * K-means
         * Generate Data
         * Explore data
         * Clustering
         * Example Application
 * [Cluster Analysis:Basic Concepts and Methods](https://github.com/Jaomiew/DWDM21/blob/main/Chapter-10-New.pdf)
     * K-Means คืออะไร?
     * Clustering แบบลำดับชั้น
     * Cluster ที่ดี มี 4 ข้อ อะไรบ้าง?

## MiniExam
   * [Mid Term](https://github.com/Jaomiew/DWDM21/blob/main/MiniExam.ipynb)

## Project
   * [Project ล่าสุด](https://github.com/Jaomiew/DWDM21/blob/main/Project_%E0%B8%A5%E0%B9%88%E0%B8%B2%E0%B8%AA%E0%B8%B8%E0%B8%94.ipynb)
   * [สไลด์นำเสนอ](https://github.com/Jaomiew/DWDM21/blob/main/NUMBERONE.pdf)

![people](S__6193162.jpg)   

