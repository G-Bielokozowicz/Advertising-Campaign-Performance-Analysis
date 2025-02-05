# Campaign Performance Analysis

## Project Overview
This project analyzes the performance of marketing campaigns using data-driven insights. The dataset includes key metrics such as **CTR, CPC, Conversions, Success Rate, and more**.

## Dataset Columns
| Column Name       | Type  | Description |
|------------------|-------|-------------|
| Campaign_ID      | Object | Unique campaign identifier |
| Budget          | Int  | Total budget for the campaign |
| Duration        | Int  | Campaign duration (days) |
| Platform        | Object | Advertising platform used |
| Content_Type    | Object | Type of content (e.g., image, video) |
| Target_Age      | Object | Age group targeted |
| Target_Gender   | Object | Gender targeted |
| Region         | Object | Geographic region |
| Clicks         | Int  | Number of clicks |
| Conversions    | Int  | Number of successful conversions |
| CTR            | Float | Click-through rate (%) |
| CPC            | Float | Cost per click ($) |
| Conversion_Rate | Float | Conversion rate (%) |
| Success        | Int  | Binary success metric (1 = Success, 0 = No Success) |
| Budget_Range   | Category | Budget classification |



##  Goals
###  **Success Rate Analysis**
- Compare **success rates** across different attributes:
  - **Age Range**
  - **Platform**
  - **Content Type**
  - **Region**

### **Budget and Duration Analysis**
- Analyze how **budget size** and **campaign duration** affect performance.

### **Platform and Content Type Performance**
- Compare CTR, CPC, and Conversion Rate across **different platforms** and **content types**.
- Identify the best-performing channels and ad formats.

### **Regional Performance Analysis**
- Assess campaign performance **across different regions**.

### **Correlation Analysis**
- Identify relationships between variables (**Budget, Clicks, Conversions, CTR, CPC, etc.**)

## Insights

Each type of content, platform and region has similar total conversion amounts.
Youtube has the highest conversion rate percentage.

## Data Analysis


## **Metric Distributions**

Every metric distributions is pretty even.
![obraz](https://github.com/user-attachments/assets/3ab27405-c4e9-4c98-9eb7-7db8217b00f5)
![obraz](https://github.com/user-attachments/assets/6196c217-ffb4-4763-bec4-467227927cb5)
![obraz](https://github.com/user-attachments/assets/8b38aa32-6653-475a-a9e2-6d1b4a326419)
![obraz](https://github.com/user-attachments/assets/833e873e-b56b-4e66-ba1b-2054d6f9af08)


![obraz](https://github.com/user-attachments/assets/22499b5a-0728-4462-affa-8f297a27d14f)


## **Succes Rate**

Majority of the campaings were considered a success.
![obraz](https://github.com/user-attachments/assets/315932c1-d4b9-4cef-ab98-d11cbe0666da)

The success rate is more than 80% acording to every metric.
![obraz](https://github.com/user-attachments/assets/7a958795-206a-413a-b2ad-ea13f4584bcc)

## **Budget and Duration Analysis**

Budget and duration of the campaign has no impact on the results.

![obraz](https://github.com/user-attachments/assets/fb4423af-1bfc-4ddb-8672-dfd7dc83826e)

![obraz](https://github.com/user-attachments/assets/a0d51e3e-fb7d-4357-813e-5de4e05b5fa4)


## **Platform Analysis**

Content type distribution per platform are close to eachother. 

![obraz](https://github.com/user-attachments/assets/48590c69-45e5-4480-8831-ba1d7d9741f5)

The most expensive platform to advertise on is youtube, but it also had the highest conversion rate.

Even though instagram and facebook had the highest click-through rate, they had lowest conversion rates.

Every platform had similar total conversion numbers.

![obraz](https://github.com/user-attachments/assets/5b1e364f-5695-42b7-b478-9c20d335302d)


## **Content Type Analysis**

Story type content is the most expensive to create, but has the highest conversion rate and click through rate.

Image has the lowest click-through rate, but very high conversion rate.

Carousel and video had the lowest conversion rate.

![obraz](https://github.com/user-attachments/assets/c443685c-ad51-4aca-94e9-45d14a994022)


## **Region Performance Analysis**

India is the most expensive region to advertise in by high margin, has the highest click-through rate, but has second lowest conversion rate.

Other regions have similar click through rates and cost per click.

![obraz](https://github.com/user-attachments/assets/3435182f-844a-46a4-a0ac-e80cd16084c2)


## **Correlation of Key Metrics**

Conversion rate is higlhy correlated with cost per click, but negativly with the amount of clicks.

![obraz](https://github.com/user-attachments/assets/83e3251e-8227-4f66-ac4f-a97a8cd13fb4)


