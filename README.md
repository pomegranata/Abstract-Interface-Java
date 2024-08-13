# Java Abstract Class and Interface - Furniture Example

Welcome to this Java repository, which focuses on the use of abstract classes and interfaces with a furniture example. This project includes various types of furniture such as general furniture, wardrobes (Almari), dining wardrobes (Almari Makan), clothing wardrobes (Almari Pakaian), tables (Meja), dining tables (Meja Makan), guest tables (Meja Tamu), and discounts.

## Table of Contents
* [Project Overview](#project-overview)
* [Features]()
* [Project Structure]()
* [Installation]()
* [Usage]()
* [Contributing]()
* [License]()
* [Contact]()

## Project Overview

This project is designed to demonstrate the use of abstract classes and interfaces in the Java programming language. By using these concepts, we can create a more structured and flexible class hierarchy for various types of furniture.

## Features

* **Abstract Class:** Provides the foundation for furniture classes.

* **Interface:** Defines common behaviors that can be applied to various types of furniture.

* **Furniture Implementation:** Includes classes for general furniture, wardrobes, dining wardrobes, clothing wardrobes, tables, dining tables, and guest tables.

* **Discount:** Implements a discount system for furniture.

## Project Structure

src/
├─ main/
│  ├─ java/
│  │  ├─ furniture/
│  │  │  ├─ Almari.java
│  │  │  ├─ AlmariMakan.java
│  │  │  ├─ AlmariPakaian.java
│  │  │  ├─ Discountable.java
│  │  │  ├─ Mebel.java
│  │  │  ├─ Meja.java
│  │  │  ├─ MejaMakan.java
│  │  │  ├─ MejaTamu.java
│  │  │  ├─ Run.java
├─ target/
│  ├─ classes/
│  │  ├─ furniture/
│  ├─ generated-sources/
│  │  ├─ annotations/
│  ├─ maven-archiver/
│  ├─ maven-status/
│  │  ├─ maven-compiler-plugin/
│  │  │  ├─ compile/
│  │  │  │  ├─ default-compile/
│  ├─ test-classes/

## Installation

To set up this project locally, follow these steps:

#### 1. Clone the repository:
```
git clone https://github.com/username/java-furniture.git
cd java-furniture
```

#### 2. Open the project in your favorite IDE (e.g., IntelliJ IDEA, NetBeans, or Eclipse)

#### 3. Build the project:
If using Maven:
```
mvn clean install
```

## Usage
To run this project, simply run the Run.java class located in:
```
src\main\java\furniture
```

## Contributing

I welcome contributions to improve this project. Please follow these steps to contribute:

1. Fork the repository.

2. Create a new branch: ``` git checkout -b feature-name ```

3. Commit your changes: ``` git commit -m 'Add some feature' ```

4. Push to the branch: ``` git push origin feature-name ```

5. Submit a pull request.