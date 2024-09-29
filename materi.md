### 1. **Variabel**:
- **Python**:  
  Di Python, variabel dapat langsung diinisialisasi tanpa mendeklarasikan tipe data terlebih dahulu. Python secara otomatis mengenali tipe data saat variabel diberikan nilai.  
  ```python
  age = 21         # integer
  name = "John"    # string
  ```
  
- **Java**:  
  Java mewajibkan Anda untuk mendeklarasikan tipe data variabel sebelum menggunakannya. Variabel harus memiliki tipe data yang spesifik, seperti `int` untuk bilangan bulat atau `String` untuk teks.  
  ```java
  int age = 21;      // integer
  String name = "John";  // string
  ```

### 2. **Tipe Data**:

#### 2.1 **Tipe Data di Python**:
Python mendukung berbagai tipe data yang tidak memerlukan deklarasi eksplisit. Berikut adalah beberapa tipe data utama yang sering digunakan:

- **Integer (int)**:  
  Digunakan untuk menyimpan bilangan bulat.  
  ```python
  number = 100  # integer
  print(type(number))  # <class 'int'>
  ```

- **Float**:  
  Menyimpan bilangan desimal.  
  ```python
  price = 99.99  # float
  print(type(price))  # <class 'float'>
  ```

- **String (str)**:  
  Digunakan untuk menyimpan teks atau rangkaian karakter.  
  ```python
  greeting = "Hello"
  print(type(greeting))  # <class 'str'>
  ```

- **Boolean (bool)**:  
  Menyimpan nilai True atau False.  
  ```python
  is_active = True
  print(type(is_active))  # <class 'bool'>
  ```

- **List**:  
  Menyimpan koleksi data yang dapat diubah dan diurutkan.  
  ```python
  fruits = ["apple", "banana", "cherry"]
  print(type(fruits))  # <class 'list'>
  ```

- **Tuple**:  
  Menyimpan koleksi data yang diurutkan tetapi tidak dapat diubah (immutable).  
  ```python
  numbers = (1, 2, 3)
  print(type(numbers))  # <class 'tuple'>
  ```

- **Dictionary (dict)**:  
  Menyimpan data dalam pasangan kunci-nilai yang tidak diurutkan.  
  ```python
  person = {"name": "Alice", "age": 30}
  print(type(person))  # <class 'dict'>
  ```

#### 2.2 **Tipe Data di Java**:
Java menggunakan pendekatan yang lebih ketat dengan mendeklarasikan tipe data sebelum variabel digunakan. Berikut adalah beberapa tipe data umum di Java:

- **Tipe Data Primitif**:
  1. **int**:  
     Menyimpan bilangan bulat.  
     ```java
     int age = 30;
     System.out.println(age);  // 30
     ```

  2. **double**:  
     Menyimpan bilangan desimal dengan presisi yang lebih tinggi dibanding float.  
     ```java
     double pi = 3.14159;
     System.out.println(pi);  // 3.14159
     ```

  3. **char**:  
     Menyimpan satu karakter.  
     ```java
     char grade = 'A';
     System.out.println(grade);  // A
     ```

  4. **boolean**:  
     Menyimpan nilai true atau false.  
     ```java
     boolean isJavaFun = true;
     System.out.println(isJavaFun);  // true
     ```

- **Tipe Data Non-Primitif**:
  1. **String**:  
     Digunakan untuk menyimpan rangkaian karakter.  
     ```java
     String greeting = "Hello World";
     System.out.println(greeting);  // Hello World
     ```

  2. **Array**:  
     Menyimpan kumpulan elemen dari tipe data yang sama.  
     ```java
     int[] numbers = {1, 2, 3};
     System.out.println(numbers[0]);  // 1
     ```

  3. **ArrayList**:  
     Mirip dengan list di Python, tetapi ukurannya dinamis.  
     ```java
     import java.util.ArrayList;

     ArrayList<String> fruits = new ArrayList<>();
     fruits.add("Apple");
     fruits.add("Banana");
     System.out.println(fruits);  // [Apple, Banana]
     ```

### 3. **Operator**:

- **Python**:  
  Python memiliki berbagai operator untuk melakukan operasi aritmatika, perbandingan, dan logika.
  ```python
  a = 5
  b = 3
  result = a * b  # 15
  is_equal = (a == b)  # False
  is_greater = (a > b)  # True
  ```

- **Java**:  
  Java juga memiliki operator yang mirip, dengan penggunaan yang sama seperti di Python.
  ```java
  int a = 5;
  int b = 3;
  int result = a * b;  // 15
  boolean isEqual = (a == b);  // false
  boolean isGreater = (a > b);  // true
  ```

### 4. **Percabangan (if-else)**:

- **Python**:  
  Dalam Python, blok kode dalam pernyataan if-else ditentukan oleh indentasi.
  ```python
  score = 85
  if score >= 75:
      print("Passed")
  else:
      print("Failed")
  ```

- **Java**:  
  Java menggunakan kurung kurawal `{}` untuk memisahkan blok kode dalam pernyataan if-else.
  ```java
  int score = 85;
  if (score >= 75) {
      System.out.println("Passed");
  } else {
      System.out.println("Failed");
  }
  ```

### 5. **Perulangan (Loop)**:

- **For Loop**:
  - **Python**:  
    Python menggunakan fungsi `range()` untuk mengatur batas loop.
    ```python
    for i in range(3):
        print(i)
    ```

  - **Java**:  
    Java menggunakan struktur perulangan for tradisional dengan deklarasi variabel, kondisi, dan update.
    ```java
    for (int i = 0; i < 3; i++) {
        System.out.println(i);
    }
    ```

- **While Loop**:
  - **Python**:  
    Loop `while` di Python terus berjalan selama kondisinya bernilai True.
    ```python
    i = 0
    while i < 3:
        print(i)
        i += 1
    ```

  - **Java**:  
    Java menggunakan sintaks serupa untuk loop `while`.
    ```java
    int i = 0;
    while (i < 3) {
        System.out.println(i);
        i++;
    }
    ```

### 6. **Fungsi (Method)**:

- **Python**:  
  Python menggunakan kata kunci `def` untuk mendeklarasikan fungsi, tanpa perlu menyatakan tipe data dari parameter atau return value.
  ```python
  def multiply(a, b):
      return a * b

  print(multiply(3, 4))  # 12
  ```

- **Java**:  
  Java membutuhkan deklarasi tipe data untuk parameter dan nilai balik dari sebuah method.
  ```java
  public int multiply(int a, int b) {
      return a * b;
  }

  System.out.println(multiply(3, 4));  // 12
  ```

### 7. **List dan Array**:

- **List di Python**:  
  List di Python dapat berisi elemen-elemen dengan tipe yang berbeda, dan ukurannya dapat berubah-ubah.
  ```python
  numbers = [1, 2, 3]
  numbers.append(4)
  print(numbers)  # [1, 2, 3, 4]
  ```

- **Array di Java**:  
  Array di Java memiliki ukuran tetap dan elemen-elemennya harus memiliki tipe yang sama.
  ```java
  int[] numbers = {1, 2, 3};
  numbers[1] = 4;
  System.out.println(numbers[1]);  // 4
  ```

- **ArrayList di Java**:  
  Untuk koleksi dinamis, Java menggunakan `ArrayList`.
  ```java
  import java.util.ArrayList;

  ArrayList<Integer> numbers = new ArrayList<>();
  numbers.add(1);
  numbers.add(2);
  System.out.println(numbers);  // [1, 2]
  ```

Java lebih ketat dalam hal deklarasi tipe data, sedangkan Python lebih fleksibel. Meski begitu, konsep dasar seperti variabel, percabangan, dan perulangan tetap serupa di kedua bahasa.
