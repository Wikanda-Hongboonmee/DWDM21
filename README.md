# DWDM21
Data Warehouse &amp; Data Mining 2021 

**_WIKANDA HONGBOONMEE  623020764-2_**

ชื่อกลุ่ม : เอกาไร้สติ

**รายชื่อสมาชิกในกลุ่ม**

1. นางสาวกัญญาวีร์ ศรีเทียมเงิน  623020511-1

2. นางสาวชลธิชา  ศาลางาม    623020518-7

3. นางสาวสุภาภรณ์  บุตุธรรม    623020543-8

4. นางสาวจิราพร   กลบรัตน์     623020762-6

5. **_นางสาววิกานดา   หงษ์บุญมี   623020764-2_**

## สารบัญเนื้อหา
### ทฤษฎี (เนื้อหา)

1. **บทที่ 1 INTRODUCTION**
   * [Lecture Chapter 1 Introduction](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter%201.pdf)
      * Data Mining คืออะไร
      * ทำไมถึงต้องทำ Data Mining 
      * Knowledge Discovery (KDD) Process
      * Data Mining in Business Intelligence
      * ตัวอย่างของข้อมูล
2. **บทที่ 2 Getting to Know Your Data**
   * Lecture Chapter 2 Getting to know your data ประกอบด้วย 3 ส่วน ดังนี้
      * [ส่วนที่ 1 Data Objects and Attribute Types](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter%202.pdf)
        * Data Object (ข้อมูล), Data Sets (ชุดข้อมูล), ตัวอย่างของข้อมูล, ขนาดของข้อมูล, Type of Data Sets (ชนิดของชุดข้อมูล)
      * [ส่วนที่ 2 Measuring Data Similarity and Dissimilarity](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Dissimilarity-distance-matrix.pdf) 
        * ความเหมือน, ความไม่เหมือน, ความแตกต่าง ของระยะห่างระหว่างจุดของข้อมูล
        * ตัวอย่างในการคำนวณหาระยะห่างระหว่างจุดของข้อมูล
      * [ส่วนที่ 3 Binary Distance](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Distance-between-Data.pdf)
        * การวัดความแตกต่างสำหรับ Binary Attributes, ตัวอย่างความแตกต่างระหว่างตัวแปรที่เป็น Asymmetric Binary Variables, การวัดความแตกต่างสำหรับ Categorical Attributes, สูตรคำนวณความแตกต่างโดยใช้ระยะห่างระหว่างจุดของตัวแปรที่เป็น Asymmetric Binary Variables และ Symmetric Binary Variables
    * [Basic Python](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Data101_(Chapter2).ipynb)
      * Variables
         * ข้อกำหนดในการตั้งตัวแปร
      * Casting int() float() stri()
      * Data Structure
         * list ()
            * string คือ list ของ ตัวหนังสือ
            * วิธีการสร้าง list แบบที่ 2 list ว่าง
               * เติมค่าลงไปใน list (.append())
               * การชี้ค่าใน list (indexing)
            * list slicing
               * [จุดเริ่มต้น: จุดสุดท้าย: step]
            * list + list
            * format string
            * Loop
               * Nested loop
            * Condition ( if statement )
               * Quiz 1 หา min
               * Homework 3 ตัดเกรด
            * Function
               * Example 1
               * Example 2 ฟังก์ชั่นที่ไม่มี input มีแต่ process กับ output
               * Example 3 ฟังก์ชั่นที่ไม่มี output มีแต่ process กับ input
               * Example 3 ฟังก์ชั่นที่ไม่มี output กับ input มีแต่ process
               * ลักษณะของ input(parameter)
               * Quiz 2    
    * [Pandas](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Data102_(Chapter2).ipynb)
      * Read Data
         * .head() .tail()
      * Boxplot
      * Time Series Plot
    * [Visualization](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Data_Visualization.ipynb)
      * Visualization
         * Box plot
         * Scatter plot
         * Plot
         * Bar chart
            * Grouped Barchart
            * Stacked Barchart
         * Histogram
    * [Distance_Numpy](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Distance_Numpy.ipynb)
      * Numpy Array
         * สร้าง Numpy Array (Matrix)
            * matrix transpose
         * สร้าง matrix เริ่มต้น (zeros, ones)
         * สร้าง matrix random
            * matrix properties
         * Indexing & Slicing ( Index - ชี้, Slice - ตัด )
         * Useful functions
         * วนลูปเอง
            * summation
         * Quiz กลุ่ม
      * Distance Matrix
         * Euclidean Distance (L2-norm)
         * Distance function
         * Manhattan Distance (L1-norm)
         * Quiz6
         * HW11
         * Distance of Binary Value
3. **บทที่ 3 Data Preprocessing**
   * [Lecture Chapter 3 Data Preprocessing](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter%203%20(Handling%20Missing).pdf)
      * Data Cleaning คืออะไร 
      * Data Integration คืออะไร
      * Data Reduction คืออะไร
      * Data Transformation และ Data Discretization คืออะไร
      * การจัดการกับ Missing Data ด้วยวิธีต่าง ๆ 
   * [Data Preprocessing](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Data_Preprocessing_(Chapter_3).ipynb)
      * Meta Data (Data ที่ใช้อธิบาย Data)
          * ชี้ข้อมูลจากตาราง
            * ชี้แบบธรรมดาใช้ [ชื่อคอลัมน์][index]
            * ชี้แบบ .iloc[] (มองข้อมูลเป็น matrix)
          * Missing values
            * Handling Missing Values 1 (ลบค่า Missing ออกไป)
              * Quiz 3 ให้หาว่า การทำ dropna() ทำให้ข้อมูลหาไปกี่ %
            * Handling Missing Value 1.5 ( ลบค่า missing เฉพาะใน column ที่เราสนใจ)
              * Quiz 3.1 ให้หาว่าการทำ dropna() แบบเลือก drop เฉพาะคอลัมน์ที่เราสนใจทำให้ข้อมูลหายไปกี่ %
            * Handing Missing Values 2 (แทนด้วย class ใหม่ (Unknow))
            * Handing Missing Values 3 ( แทนด้วย class ใหม่ (ค่าที่เหมาะสม))
            * Handling Missing Values 4 ( แทนด้วยค่ากลาง)
              * ถ้าเป็นตัวเลขหรือ numeric ใช้ mean
              * ถ้าเป็นตัวหนังสือ หรือ norminal เราจะแทนด้วย mode
              * ถ้าเป็น ordinal ใช้ median
            * Handling Missing Values 5 ( แทนด้วยค่ากลางของ sample ใน class เดียวกัน )
          * Select data by values[PD]
              * สร้าง list ของ boolean
                * นำ list ของ boolean มาเลือกค่าในตาราง
          * Quiz 4 + Homework
                * 1. records ที่ กักตัวที่ขอนแก่น
                * 2. records ที่ กักตัวที่ ขอนแก่น+โคราช+อุดร
                * 3. records ที่ เป็นผู้หญิงที่พบเชื้อที่ กทม
                * 4. records ที่ เป็นผู้ชาย อายุ 18-22 ปี ที่กักตัวที่เชียงใหม่
                * 5. หาอายุเฉลี่ยของคนที่พบเชื้อที่ขอนแก่น
          * Handling Missing Values 5 (ต่อ)
          * การเรียงข้อมูล [PD]
      * Outlier
          * ตัด outlier แบบ manual
      * HW8 + Quiz 5
      * การบ้านกลุ่ม (III)
      * การรวมตาราง Data integration (ต่อตารางในแนวแกน X)
          * เลือกเฉพาะคอลัมน์ที่ต้องการมาแปะ (.map())
          * ตารางรองควรจะต้องไม่มี index ซ้ำ
          * Group by (pandas)
      * HW 10 + Quiz
      * [PD] save ตารางเอาไปใช้ที่อื่น
      * [PD] การสร้างตาราง
4. **บทที่ 4 Data Warehousing and On-line Analytical Processing**
   * [Lecture Chapter 4 Data Warehousing and On-line Analytical Processing](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Data%20Cube%20%26%20OLAP.pdf)
      * Data Warehouse คืออะไร
      * Data Cubes
      * Typical OLAP Operations
5. **บทที่ 5 Association Rules**
   * [Lecture Chapter 5 Mining Frequent Patterns, Association and Correlations:Basic Concepts and Methods](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Association%20rules.pdf)
      * Patterns คืออะไร
      * การค้นพบรูปแบบหรือ Pattern ของข้อมูลมีความสำคัญอย่างไรบ้าง
      * K-Itemsets
      * Frequent Itemsets (Patterns)
      * Mining Frequent Itemsets
      * Association Rules
      * Apriori Algorithm คืออะไร / ตัวอย่างของ Apriori Algorithm 
  * [Reduced_marketbasket](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter_6_Association_Rules.ipynb)
      * ลบ records ที่ถูก cancel ออกไป
      * มีประเทศสาขาของ Supermarket นี้ทั้งหมดกี่ประเทศ
      * HW 13 วาดกราฟสรุปจำนวน items และยอดขายของแต่ละประเทศ
      * เตรียม Data สำหรับ (Frequence Pattern) Association Rule
      * Apriori
        * แปลความหมาย
        * Quiz 7 หา k-itemset ที่มีความน่าสนใจ (โดยพิจารณาลูกค้าเป็นรายคน) พร้อมอธิบายว่าน่าสนใจยังไง
        * แปลความหมายของผลลัพธ์
6. **บทที่ 6 Classification**
  * Lecture Chapter 6 Classification:Basic Concepts 
      * [ส่วนที่ 1 Lecture Classification: Basic Concepts](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Decision-Tree.pdf)
         * การสร้างโมเดลแบบมีผู้สอน/การสร้างโมเดลแบบไม่มีผู้สอน
         * Classification (การสร้าง model เพื่อนำ feature มาใช้ในการทำนายคำตอบ)
         * Decision Tree Induction (การทำนายโดยใช้วิธีต้นไม้ตัดสินใจ)
         * การเลือก Attribute โดยคำนวณหาค่า Information Gain 
         * ตัวอย่างการคำนวณ 
         * [HW Decision Tree คำนวณมือ](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Decision-Tree.pdf)
      * ส่วนที่ 2 Lecture Decision Tree
         * [Decision Tree Induction: Algorithm](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Precision%20%26%20Recall%20%26%20F-measures.pdf)
            * Overfitting & Tree Prunning (ตัดแต่งกิ่งต้นไม้)
      * [Decision Tree](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter_7_Classification_(Decision_Tree).ipynb)
        * Load Data
        * Train Model
          * import (เรียกใช้อัลกอริทึมที่เราต้องการ)
          * define (กำหนดพารามิเตอร์ให้กับ model)
          * train (ฝึกสอนตัวแบบ)
          * plot tree
        * Evaluation
          * Random
        * Advanced Tree
          * import
          * Define
          * Train
          * TEST
            * Start here
        * HW
          * 1. ต้นไม้ที่ใช้เกณฑ์ Entropy มีความสูงไม่เกิน 4 ชั้น
              * Import
              * Define
              * Train
              * Evaluate
              * Test
          * 2. ต้นไม้ที่ใช้เกณฑ์ Gini มีใบไม่เกิน 25 ใบ
              * Import
              * Define
              * Train
              * Evaluate
              * Test
          * 3. ต้นไม้ที่ใช้เกณฑ์ Entropy และใช้การ split แบบ random
              * Import
              * Define
              * Train
              * Evaluate
              * Test
          * 4. ต้นไม้ที่เราคิดเอง
              * Import
              * Define
              * Train
              * Evaluate
              * Test
          * เลือก T4 แล้ว Train ใหม่ด้วย Training
      * ส่วนที่ 3 Lecture k-Nearest Neighbor
         * [Naïve Bayes Classifier](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Precision%20%26%20Recall%20%26%20F-measures.pdf)
            * วิธีการ Training Datasets ของ Naïve Bayes Classifier
            * ตัวอย่างการคำนวณ
         * [Lazy Learner:Instance-Based Mathods](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Naive%20Bayes%20%26%20KNN.pdf)
         * [K-nearest neighbors approach](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Naive%20Bayes%20%26%20KNN.pdf)
     * [k-Nearest Neighbor & Neural Networks](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter_7_Classification_(KNN_NN).ipynb)
       * Load Data
       * Split Data
       * Train Model
          * Import
          * KNN1
          * KNN2
          * KNN3
       * Retain & Evaluate
       * Neural Network
          * Import
          * Define
          * Train-Test
          * ANN2
          * ANN3
     * ส่วนที่ 4 Lecture Neural Networks & Evaluation      
       * [Neural Network](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter%209%20Neural%20Network.pdf)
       * [เพอร์เซปตรอน (perceptron)](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/%E0%B9%80%E0%B8%AD%E0%B8%81%E0%B8%AA%E0%B8%B2%E0%B8%A3%E0%B9%80%E0%B8%9E%E0%B8%B4%E0%B9%88%E0%B8%A1%E0%B9%80%E0%B8%95%E0%B8%B4%E0%B8%A1.pdf)
          * กฏการเรียนรู้เพอร์เซปตรอน
          * ตัวอย่างการเรียนฟังก์ชัน AND/XOR ด้วยกฏการเรียนรู้เพอร์เซปตรอน
      * [Classifier Evaluation Metrics](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Precision%20%26%20Recall%20%26%20F-measures.pdf)
         * Confusion Matrix, Accuracy, Error Rate, Sensitivity and Specificity
         * Precision, Recall and F-measures
         * ตัวอย่างการคำนวณ
    * [Evaluation](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter_7_Classification_(Evaluation).ipynb)
      * Load data
        * แบ่ง Data ออกเป็น 2 ส่วน
        * สร้าง Model เพื่อนำมาใช้ในการทำนาย
          * Import
          * Define
          * Train
          * Evaluation
7. **บทที่ 7 Clustering**
  * [Lecture Chapter 7 Cluster Analysis:Basic Concepts and Methods](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter%2010%20Cluster%20Analysis.pdf)
    * K-Means คืออะไร
    * ตัวอย่างการคำนวณหาค่า K-Means
    * Dendrogram (การทำ Clustering แบบลำดับชั้น)
    * Clustering Validation & Assessment
    * Measuring Clustering Quality (วิธีการวัดผล)/External & Internal Methods
    * Internal Measures: BetaCV Measure (กรณีที่ไม่รู้คำตอบ)
  * [Clustering](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Chapter_8_Clustering.ipynb)
    * K-means
      * Generate Data
      * Explore Data
      * Clustering
        * Import
        * Define
        * Fit-Predict
        * 3 Cluster
        * 4 Cluster
        * 5 Cluster
      * Example Application (Color Quantization)
        * นับจำนวนสี
        * จัดกลุ่มสีให้เหลือ 16 สี
        * แปลงข้อมูลให้อยู่ในรูป row-column
        * ใช้ centroid เป็นตัวแทนของสี
* [MiniExam](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/MiniExam.ipynb)
* [Group Project](https://github.com/Wikanda-Hongboonmee/DWDM21/blob/main/Project_DWDM.ipynb)
   * Project กลุ่ม
      * รายชื่อสมาชิกในกลุ่ม
      * แหล่งที่มาของข้อมูล
      * ปัญหา
      * ชุดข้อมูลที่ 1 รับเรื่องร้องเรียน/แจ้งเบาะแสยาเสพติด
         * คำอธิบายตาราง
         * ตรวจสอบค่า Missing ของตาราง data_01
      * ชุดข้อมูลที่ 2 ปริมาณของกลางยาเสพติด
         * คำอธิบายตาราง
         * ตรวจสอบค่า Missing ของตาราง data_02
      * ชุดข้อมูลที่ 3 จำนวนคดี ผู้ต้องหาคดียาเสพติด
         * คำอธิบายตาราง
         * ตรวจสอบค่า Missing ของตาราง data_03
      * ข้อมูลชุดที่ 4 ข้อมูลทั่วไปของจังหวัด
         * คำอธิบายตาราง
         * ตรวจสอบค่า Missing ของตาราง data_04
      * เชื่อมต่อตาราง
         * ตรวจสอบค่า Missing ของตาราง 2 ตารางที่เชื่อมต่อกันแล้ว
         * ตรวจสอบค่า Missing ของตาราง 3 ตารางที่เชื่อมต่อกันแล้ว
      * Classification
         * ปัญหา
         * เลือกคอลัมน์ที่ต้องการนำมาใช้งาน
         * Decision Tree
         * KNN
         * Neural Network
      * Evaluation
         * Retain & Evaluation
      * Data_Visualization
      * THE END
