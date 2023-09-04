# Project Name
> Lending Club Case Study

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
* Lending Club is a largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

* Borrower applies for the loan(loan_amnt) by providing their income(annual_inc), credit quality score, professional experience(emp_length), and for what purpose they are applying the loan(purpose and title) and which place they are staying(addr_state) and are they staying in their own house / rent / mortgage (home_ownership)

* Lending club shares the request with the investors.

* If once they validated the details, they will share how much amount got approved by investors(funded_amnt_inv) and their rate of interest(int_rate) and (grade) and (sub_grade) will get decided

* Borrower will choose the term period (term - 36 months / 60 months) to repay the amount along with the interest
- > Find the driving factors which lead to the defaulted loans which are major source of loss for the company.
- The data set is a csv(loan.csv) file with the loan data for the Lending Club.

## Conclusions

Grade, SubGrade - As grade changes there are defaulters changing, G being the highest
Purpose of the loan - Small business has more defaulters
Interest rate - As interest rate increases defaulters are moe 
Term - There are more defaulters with 60 months term than 36 months
Annual income - If the annual income is more then high possibility that he pays the loan

#Stop High Risk Loans
grade F
int_rate > 20%

#Reduce Medium Risk Loans
grade > 'C'
int_rate > 12.5%
annual_inc < 15000
term = 60 months

#Increase Low Risk Loans
grade 'A'
int_rate 7.5-10%
term = 36 months
lesser loan amount
lower dti



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Numpy 1.23.5
Pandas 1.5.3
Seaborn 0.12.2
matplotlib 3.7.0
MS Powerpoint 2019

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Artificial Intelligence and Machine course.

## Contact
Created by [@icsaiml] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
