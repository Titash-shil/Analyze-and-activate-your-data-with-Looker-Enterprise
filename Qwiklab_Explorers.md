#  || [Analyze and activate your data with Looker Enterprise](https://www.cloudskillsboost.google/focuses/88314?parent=catalog) || 

## # Like, comment, share & Don't forget to subscribe [Qwiklab_Explorers](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN) 👍😄🤝

---
## ⚠️ **Disclaimer:**
#### This script and guide are provided for educational purposes to help you understand the lab process. Please ensure you understand the steps before using any scripts. Before using the script, I encourage you to open and review it to understand each step.The goal is to help you learn how to complete the labs effectively while following Qwiklabs' terms of service and YouTube's community guidelines.
---

- # Follow the all steps mentioned bellow to complete the lab : ⬇⬇

 - ###  First, on the bottom left of the Looker User Interface, click the toggle button to enter `Development mode`.
 - ### Click the Develop tab and then select the fintech.
 - ### Open fintech.model file and paste the below code.
```


# Place in `fintech` model
explore: +loan_details {
    query: QwikLab_Explorers_task_2 {
      measures: [loan.outstanding_loans_amount]
    }
}



# Place in `fintech` model
explore: +loan_details {
    query: QwikLab_Explorers_task_3 {
      dimensions: [loan.loan_status]
      measures: [loan.outstanding_loans_amount]
    }
}




# Place in `fintech` model
explore: +loan_details {
    query: QwikLab_Explorers_task_4 {
      dimensions: [loan.state]
      measures: [loan.outstanding_count]
    }
}


# Place in `fintech` model
explore: +loan_details {
    query: QwikLab_Explorers_task_5 {
      dimensions: [
        customer.address_state,
        customer.annual_income,
        customer.customer_id,
        customer.home_ownership,
        loan.interest_rate,
        loan.loan_status
      ]
    }
}

```
---
- ###  LAB TASK 2 🕹️
---
- Edit Visualization ➡️ Formatting ➡️ Conditional Formatting : `Enable` ➡️ Add Rule : Change the background color to `red`  & The value is greater than `3000000000` ➡️ Run ➡️ Save.
- Create Dashboard Name as :  `Loan Insights`.
- Save Title Name as :  `Total Amount of Outstanding Loans`.

---

- ### LAB TASK 3 🕹️
- Visualization Type : `pie chart`. 
- Save Title Name as :  `Percentage of Outstanding Loans`.

---

### LAB TASK 4 🕹️ 
- Row Limit : `10`. ➡️ Visualization : `bar chart`.
- Save Title Name as :  `Total Count of Outstanding Loans`.

---

### LAB TASK 5 🕹️
- Row Limit : `10`. ➡️ Visualization Type : `Table`. ➡️ Annual Income type : `Descending` ⬇️
- Save Title Name as :  `Top 10 Customers by Highest Income`.

---

## Congratulations ..!!🎉  You completed the lab shortly..😃💯

## *Well done..!* 👏

## Thank you for visiting.... :) 🗯️

## [Qwiklab_Explorers_ts](https://youtube.com/@titashshil?si=RgamNu1dc9jVIbJN)

## Join to our community [Digital Dominators](https://chat.whatsapp.com/J0o1beFGCHfJ8ZHGKjcqkd)
