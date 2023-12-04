# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API with no auth and no CORS from the following list. It _should not_ be one that you've already seen or worked on in class.
   - [Public APIs](https://github.com/public-apis/public-apis)
1. Choose an API not covered in your readings, class, or other assignments. The API should be new to you.
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.
1. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

## Instructions

Do your best to answer the questions with specific details. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL.

> https://open-meteo.com/en/docs

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it. 

> The purpose of this API is for weather forecasting apps, offering up to 16 days forecast. Multi locations and hourly weather variables.

- What is the URL of the documentation?

> https://api.open-meteo.com/v1/forecast?latitude=52.52&longitude=13.41&hourly=temperature_2m

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://api.open-meteo.com/v1/forecast

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "latitude": 52.52,
    "longitude": 13.419998,
    "generationtime_ms": 0.049948692321777344,
    "utc_offset_seconds": 0,
    "timezone": "GMT",
    "timezone_abbreviation": "GMT",
    "elevation": 38.0,
    "hourly_units": {
        "time": "unixtime",
        "temperature_2m": "°C"
    },
    "hourly": {
        "time": [
            1701648000,
            1701651600,
            1701655200,
            1701658800,
            1701662400,
            1701666000,
            1701669600,
            1701673200,
            1701676800,
            1701680400,
            1701684000,
            1701687600,
            1701691200,
            1701694800,
            1701698400,
            1701702000,
            1701705600,
            1701709200,
            1701712800,
            1701716400,
            1701720000,
            1701723600,
            1701727200,
            1701730800,
            1701734400,
            1701738000,
            1701741600,
            1701745200,
            1701748800,
            1701752400,
            1701756000,
            1701759600,
            1701763200,
            1701766800,
            1701770400,
            1701774000,
            1701777600,
            1701781200,
            1701784800,
            1701788400,
            1701792000,
            1701795600,
            1701799200,
            1701802800,
            1701806400,
            1701810000,
            1701813600,
            1701817200,
            1701820800,
            1701824400,
            1701828000,
            1701831600,
            1701835200,
            1701838800,
            1701842400,
            1701846000,
            1701849600,
            1701853200,
            1701856800,
            1701860400,
            1701864000,
            1701867600,
            1701871200,
            1701874800,
            1701878400,
            1701882000,
            1701885600,
            1701889200,
            1701892800,
            1701896400,
            1701900000,
            1701903600,
            1701907200,
            1701910800,
            1701914400,
            1701918000,
            1701921600,
            1701925200,
            1701928800,
            1701932400,
            1701936000,
            1701939600,
            1701943200,
            1701946800,
            1701950400,
            1701954000,
            1701957600,
            1701961200,
            1701964800,
            1701968400,
            1701972000,
            1701975600,
            1701979200,
            1701982800,
            1701986400,
            1701990000,
            1701993600,
            1701997200,
            1702000800,
            1702004400,
            1702008000,
            1702011600,
            1702015200,
            1702018800,
            1702022400,
            1702026000,
            1702029600,
            1702033200,
            1702036800,
            1702040400,
            1702044000,
            1702047600,
            1702051200,
            1702054800,
            1702058400,
            1702062000,
            1702065600,
            1702069200,
            1702072800,
            1702076400,
            1702080000,
            1702083600,
            1702087200,
            1702090800,
            1702094400,
            1702098000,
            1702101600,
            1702105200,
            1702108800,
            1702112400,
            1702116000,
            1702119600,
            1702123200,
            1702126800,
            1702130400,
            1702134000,
            1702137600,
            1702141200,
            1702144800,
            1702148400,
            1702152000,
            1702155600,
            1702159200,
            1702162800,
            1702166400,
            1702170000,
            1702173600,
            1702177200,
            1702180800,
            1702184400,
            1702188000,
            1702191600,
            1702195200,
            1702198800,
            1702202400,
            1702206000,
            1702209600,
            1702213200,
            1702216800,
            1702220400,
            1702224000,
            1702227600,
            1702231200,
            1702234800,
            1702238400,
            1702242000,
            1702245600,
            1702249200
        ],
        "temperature_2m": [
            -4.8,
            -5.1,
            -5.1,
            -5.4,
            -5.3,
            -5.1,
            -5.3,
            -5.1,
            -4.5,
            -3.5,
            -2.7,
            -1.9,
            -1.7,
            -1.4,
            -1.4,
            -1.4,
            -1.7,
            -1.7,
            -1.7,
            -1.9,
            -2.3,
            -2.5,
            -2.5,
            -2.6,
            -2.8,
            -3.0,
            -3.1,
            -3.0,
            -2.9,
            -2.8,
            -2.6,
            -2.5,
            -2.5,
            -2.2,
            -1.8,
            -1.5,
            -1.5,
            -1.3,
            -1.2,
            -1.1,
            -1.0,
            -0.8,
            -0.7,
            -0.6,
            -0.5,
            -0.4,
            -0.2,
            -0.1,
            -0.0,
            0.1,
            0.2,
            0.2,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.4,
            0.5,
            0.5,
            0.5,
            0.5,
            0.4,
            0.4,
            0.3,
            0.2,
            0.4,
            0.3,
            0.3,
            0.2,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.2,
            0.2,
            0.2,
            0.3,
            0.6,
            0.9,
            1.0,
            0.9,
            0.8,
            0.7,
            0.5,
            0.5,
            0.5,
            0.5,
            0.6,
            0.6,
            0.4,
            0.2,
            -0.0,
            -0.2,
            -0.3,
            -0.5,
            -0.6,
            -0.7,
            -0.7,
            -0.6,
            -0.5,
            -0.3,
            -0.1,
            0.1,
            0.2,
            0.3,
            0.4,
            0.4,
            0.4,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.3,
            0.4,
            0.4,
            0.5,
            0.5,
            0.6,
            0.6,
            0.7,
            0.9,
            1.1,
            1.3,
            1.5,
            1.5,
            1.4,
            1.3,
            1.2,
            1.1,
            1.1,
            1.1,
            1.1,
            1.1,
            1.0,
            0.9,
            0.9,
            1.0,
            1.0,
            0.9,
            0.9,
            1.0,
            1.4,
            1.9,
            2.4,
            2.8,
            3.2,
            3.5,
            3.8,
            4.1,
            4.3,
            4.4,
            4.4,
            4.4,
            4.4,
            4.4,
            4.5,
            4.5,
            4.6
        ]
    }
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`:application/json; charset=utf-8



> `Content-Length`:600



- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

>> The data we received includes latitude, longtiude, timezone, elevation and hourly units of the time and temperature .
>>

- Identify at least two ways to use the data within a web application.

>> I could imagine integrating this API into an app that provides the weather for various locations thorughout the world using realtime data. The data can be used for a weather app and to determine the geo location of the user.
>>
### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was concise, clear and not overly dense and complicated. 
>
- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation slightly overwhelming with the filters for variouss weather climate ensemble models involving marine forecast, geocoding, climate change, elevation and flood categories.
.

- Did the quality of the documentation impact your decision to use it?

> Yes because overly compliacted documentton would make app functionality more difficult for me, the developer.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> No I ended up only switching the api bran due to authoriztion key issues, however the category of api has remained consistent.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is the transfer of forms making requests and ensuring the proper keys and objects line up so the data flow makes sense to the data servers talking to each other and ultimately to the end user.

- In your own words, describe what an API is.

> An API is a data flow being managed by servers and code ensuring what is requested is in line with whats expected.

- In your own words, describe the purpose of Postman.

>> Postman is an application that simplifies the request response cycle by seperating the 4 elements of the request response cycle into sub categories of the most necesary data, metadata, json etc, and allows the developer to sift, sort and filter through the data needed with specificity without getting into the weeds.
>>
