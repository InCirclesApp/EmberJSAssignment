## EmberJS Assignment

### Covid-19 Dashboard

Doctors, epidemiologists, and specialists need to take a fast response to the current COVID-19 outbreak.
For that, they need as much data as possible to make the correct decisions.
You are assigned to develop a COVID-19 Dashboard to help them.

#### 1. Summary

The Dashboard should allow anyone to see at a glance the current status of the COVID-19 infections around the world.
It should also allow users to search for a country to display its data and, possibly, compare it with Germany's data.

#### 2. Product Requirements

- **Overall global summary**

- **Country selector**

  It can be a dropdown, autocomplete text input, or whatever means of selecting the countries available on the API.

- **Country data**

  After the user selected a country, the Dashboard should display the following details:

  - Total confirmed cases
  - Percentage of the world's confirmed cases
  
- **Routes**
  Your app should be structured in two pages.
  The first should contain the Global Summary and the country selector, and the second showing the selected country's data.

- **Tests**
  Implement some unit tests.
- **Extra**
  On the country detail page, for extra points, show a country comparison with all the available German data on the API.

#### 3. Technical requirements

- [EmberJS v2.18](https://guides.emberjs.com/v2.18.0/)
- Node v12
- [COVID-19 API](https://covid19api.com/)

#### 4. Deployment

No deployment is needed. You can either send the code in a ZIP file via e-mail or create a private Github repository and add us as contributors.

#### 5. Remarks

* Send your code in a structured Git repository.
* If you feel adventurous, feel free to increment the assignment with more data, but don't stress it.
