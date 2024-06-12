## Model Details

### Model Description
- **Developed by:** Cynaptics Club
- **Model type:** Large Language Models (LLMs)
- **Language(s) (NLP):** 
- **License:** 
- **Finetuned from model:** ORPO, SFT, DPO

## Uses

The SQL Coder model is designed to assist users in generating, optimizing, and understanding SQL queries. Leveraging advanced machine learning techniques, the model provides accurate and efficient SQL code solutions based on user inputs, making it an invaluable tool for both novice and experienced database administrators, developers, and data analysts.

### Direct Use

Efficiently generate, optimize, and debug SQL queries from natural language descriptions, enhancing productivity and query performance for developers and data analysts.

### Downstream Use

Enhance database management, improve data retrieval speed, support advanced data analysis, and aid in learning SQL by providing clear explanations and optimized query solutions.

### Out-of-Scope Use

Out of scope uses for the SQL Coder model include generating SQL queries for unsupported or non-relational databases, performing complex database administration tasks such as backup and restore, providing comprehensive data visualization and reporting tools, and writing application-specific business logic outside of SQL queries.

## Bias, Risks, and Limitations


### Recommendations

<!-- This section is meant to convey recommendations with respect to the bias, risk, and technical limitations. -->

## How to Get Started with the Model

Use the code below to get started with the model.



## Training Details

### Training Data
In our analysis and experiments, we employ various SQL datasets. These datasets serve as valuable resources for training and evaluating text-to-SQL models, facilitating a deeper comprehension of query types and SQL syntax.Individual Dataset Information
- Text2SQL
- b-mc2/sql-create-context
- Clinton/Text-to-sql-v1
- zerolink/zsql-sqlite-dpo
- xlangai/spider
- PipableAI/pip-txt-to-sql-spider-bird-dataset
- gretelai/synthetic_text_to_sql
- NumbersStation/NSText2SQL

#### Training Hyperparameters

- **Total Entries:** 15,50,168
- **Self Join:** 2,76,296
- **Left Join Understanding:** 18,794
- **Case statement:** 20,148
- **Window Function:** 2297
- **User Defined Function:** 336

#### Speeds, Sizes, Times

<!-- This section provides information about throughput, start/end time, checkpoint size if relevant, etc. -->

## Evaluation

<!-- This section describes the evaluation protocols and provides the results. -->

### Testing Data, Factors & Metrics

#### Testing Data

#### Metrics

### Results

From our evaluation these base models were performing pretty well and hence fine tuning them will necessarily improve their performance

#### Summary

The SQL Coder model has been fine-tuned using techniques such as SFT, DPO, ORPO, and DNO. By creating our own dataset and incorporating benchmarking datasets, we achieved results on par with other leading models. This advanced model efficiently generates, optimizes, and debugs SQL queries, significantly enhancing productivity and query performance for developers and data analysts.

### Model Architecture and Objective

## Model Card Authors [optional]

Cynaptics Club, IIT Indore

