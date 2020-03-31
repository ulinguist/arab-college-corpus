## ArabCC: EFL Learners' Corpus
### The Arab Academic College of Education

A research project led by [Dr. Omaima Abboud](https://www.linkedin.com/in/omaima-abboud-915668149/?originalSubdomain=il) together with [Dr. Noam Ordan](https://scholar.google.com/citations?user=-Xtm8iAAAAAJ&hl=en). The corpus data is curated by [Uliana Sentsova](https://www.linkedin.com/in/uli/) (the owner of the current repository).

For any questions about the data, please do not hesitate to contact me directly via email: uliana.sentsova@gmail.com.

### Corpus Description

ArabCC is a corpus of English essays written by native speakers of the Arabic language.


The directory of the project contains the following files and folders:

```
metadata.tsv
README
essays/
```

The `essays` folder contains 957 files in text format, each file corresponds to an essay and each filename corresponds to the ID of that essay. The folder has 1.1 MB of data.

The `metadata.tsv` file contains detailed information about essays, such as ID, student ID, student's level, etc. You can use the metadata file with the `pandas` library, as shown in the Examples section.

The metadata consists of 957 rows and 5 columns, namely: **Essay ID**, **Student ID**, **Level**, **Prompt**, **Date**.

The **ID** column contains identification numbers of each essay. ID is equal to the name of the file in the `essays` folder. Data type is integer.

The **Level** column contains codes of nine education levels. Data type is categorical (ordinal). See the following list for the meaning of each code:

- `HS-9` high school students, 9th grade
- `HS-10`: high school students, 10th grade
- `HS-11`: high school students, 11th grade
- `HS-12`: high school students, 12th grade
- `BA-0`: students to be admitted for a BA programme at the Arab Academic College of Education 
- `BA-1`: BA programme students, first year
- `BA-2`: BA programme students, second year
- `BA-3`: BA programme students, third year
- `MA-1`: MA programme students, first year



### Corpus Statistics

- Number of essays: 957
- Number of prompts: 39
- Number of tokens: 203654
- Number of types: 6619
- Number of lemmas: 4894
- Average number of tokens per text: 213
- Approximate number of sentences: 10246


### Students Information
- Total number of students: 304
    - To-be-admitted students:	34
    - High school students:	141
    - BA students:	484
    - MA students:	298
