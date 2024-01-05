## US and EU Sanctions on Russia after 2014

This code is part of my master's thesis in which I examine the impact of US and EU sanctions on Russia after its annexation of Crimea in 2014. It is a work in progress and will be updated regularly. The raw data is from the US Office of Foreign Assets Control [(OFAC)](https://ofac.treasury.gov/) and the Council of the European Union [(EU Council)](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX%3A02014D0145-20230915&qid=1703029680787). The code cleans these officialy sanctions lists, divides them each into targeted individuals and targeted entities, and then merges them to a comprehensive list of sanctioned individuals and sanctioned entities. It then identifies firms that are not explicitly mentioned in the sanctions list, but are nevertheless sanctioned for one of the following reasons:
- Their Global Ultimate Owner (GUO) was sanctioned
- Their Majority Shareholder was sanctioned
- Their are a subsidiary of a sanctioned firm

Finally, the code matches the comprehensive dataset of all targeted entities with data on economic performance from the [ORBIS](https://www.bvdinfo.com/en-gb/) Europe dataset.

Below are some summary statistics of the of the final dataset.

### **Sanctioned Firms across Industries**


![Untitled](https://github.com/Lisagmrk/Masters-Thesis/assets/64646346/06a129af-59c8-4f78-bc8e-a2193fe79a5d)

![image](https://github.com/Lisagmrk/Masters-Thesis/assets/64646346/fb992822-a519-42f2-9c5d-2dd2a5683c06)

### **Sanctioned Firms by Sanctioning Government**

![Untitled-1](https://github.com/Lisagmrk/Masters-Thesis/assets/64646346/7c8bcab7-4e38-47f5-9bb1-727a4ae005b4)

### **Total Number of Sanctioned Firms in 2014**

![Untitled](https://github.com/Lisagmrk/Masters-Thesis/assets/64646346/1a7d826f-3a17-4a2f-af8c-5ba03d36d5ff)

### **Number of Sanctioned Firms by Type**

![Untitled-1](https://github.com/Lisagmrk/Masters-Thesis/assets/64646346/8278d2f2-323c-4fab-a4ae-e93e9b63c5b0)




