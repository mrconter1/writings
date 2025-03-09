# Forecasting Project

This project aims to forecast societal expectations regarding humanoid robots performing intuitive household tasks.

## Methodology

Data will be collected through personal or phone interviews conducted one-on-one with each participant. 

All collected data will be stored in `data.json` in the following format:
```json
{
  "participants": [
    {
      "date_of_interview": "YYYY-MM-DD",
      "first_name": "Name",
      "birth_year": "YYYY",
      "gender": "Gender",
      "occupation_profession": "Occupation",
      "education": "Education",
      "response": "Detailed response...",
      "years_prediction": "N"
    }
  ]
}
```

## Forecasting Question

How many years do you think it will take until you reach a point where seeing a humanoid robot performing everyday tasks in a regular home no longer surprises you, and you naturally expect it to perform at an average human level when you ask it to do things like the following:

1. "I have some wall plaster on the shelf in the storage area in the kitchen. I think there's a putty knife there as well. Can you fix all the holes in the whole apartment?"
2. "My piano is getting a bit dusty. Can you clean it up?"
3. "Can you water and fix up my plants? Like remove the yellow and brown leaves and so on."
4. "Can you do my dishes? (where you don't have a dishwasher)"
5. "Can you fold my clean pile of laundry?"
6. "I have some frozen salmon in the fridge, can you make a dish for me using that?"
7. "Can you change my bedclothes?"
8. "Can you tune my guitar?"
9. "Can you vacuum clean? (where you have to do it manually)" 