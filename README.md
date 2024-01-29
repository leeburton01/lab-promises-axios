![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# LAB | Promises Axios

<details>
  <summary>
   <h2>Learning Goals</h2>
  </summary>


  This exercise allows you to practice and apply the concepts and techniques taught in class. 

  Upon completion of this exercise, you will be able to:

  - Handle promises using .then() and async await.
  - Use Axios to communicate with an external API.
  <br>

  <hr> 


</details>

## Introduction

This lab will be using the information learned today over handling promises and communicating with an external API.

## Setup

- Fork this repo

- Clone the forked repo

- Open the LAB and start:

  ```bash
  cd lab-react-ironnutrition-vite
  npm install
  npm run dev
  ```

## Submission

- Upon completion, run the following commands:

  ```bash
  git add .
  git commit -m "done"
  git push origin master
  ```

- Create a Pull Request and submit your assignment.

<br>




## Instructions

### Iteration 1 | Fetch the data for Darth Vader
  In this iteration we will start off with a straightforward implementation. We will fetch the data for the object containing Darth Vaders information from the Star Wars API and console.log the result.
<br/>
  Endpoint for Darth Vader Information:
    
  ```shell
https://swapi.dev/api/people/4
```
Expected Result:
<br/>
![image](https://github.com/November-cohort-2023/lab-promises-axios/assets/54825038/95a62c38-9bcb-48e4-be16-3ac3a2581a66)

### Iteration 2 | Fetch the data for the country of France

In this iteration we will use the restcountries API. Fetch the information for the country of france from the restcountries api and console.log() the name of the country.
<br/>
#### Hint: Check the structure of the object to get the exact . notation for the name of of the country
<br/>
   
     Endpoint for France: https://restcountries.com/v3.1/name/france



<br/>
Expected Results:


![image](https://github.com/November-cohort-2023/lab-promises-axios/assets/54825038/231fab31-226b-4f83-986f-f5719adf3506)



### Iteration 3 | Fetch the data for all countries

Now that we have fetched the data for France let's fetch the data for all the countries and console.log the first 10 values we recieve from the API. 

<br/>


  Endpoint for all countries: https://restcountries.com/v3.1/all



<br/>


![image](https://github.com/November-cohort-2023/lab-promises-axios/assets/54825038/bd346ce8-b1da-4da0-bd3d-e6347d656da2)


### BONUS: Iteration 4 | Use async await to handle the promises

In this iteration we will handle the previous promises using async await. If you used async await for the previous iterations than practice using .then()


