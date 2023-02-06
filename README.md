# Tineo_Bryan_M3_Group_Challenge
NETFLIX BOOTCAMP CHALLENGE #3

In this project, you will work together with a team to build a REST API. It will provide a quote of the day, a word of the day, and Magic 8 Ball services. In addition, you will produce a 1 to 3 minute video summary of the project.

User Stories

Your project must implement the following user stories:

    As an API user, I want to request a random quote so that I can expand my knowledge.

    As an API user, I want to request a random word and its definition so that I can expand my vocabulary.

    As an API user, I want to request a random answer to a question so that I can be entertained.

Requirements
General Setup and Format

    Your project must be created in an IntelliJ project called Summative-1-Lastname-Firstname.

    Your project must be built using Spring Boot and Spring MVC.
        Initialize the project using start.spring.io.

    Your project must have a series of tests using MockMvc.

    Your project must use in-memory data that follows the pattern demonstrated previously in this module.

    Your REST API must accept and return data in JSON format where appropriate.

    Your REST API must be documented using Swagger.
        Save the .yaml file in the root of the project directory.

Quote API

The Quote API provides a quote of the day service and must implement the following route:

    URI: /quote

    Method: GET

    Request Body: None

    Response Body: Quote

The Quote model should include the following:

    id

    author

    quote

Word API

The Word API provides a word of the day service and must implement the following route:

    URI: /word

    Method: GET

    Request Body: None

    Response Body: Definition

The Definition model should include the following:

    id

    word

    definition

Magic 8 Ball API

The Magic 8 Ball API provides a magic 8 ball service and must implement the following route:

    URI: /magic

    Method: POST

    Request Body: Question

    Response Body: Answer
        The POST request for the Magic 8 Ball endpoint should include a user-provided question.
    note

    You are not required to include any model validations for this summative project. This means that it is possible to submit the Magic 8 Ball POST request without a question, and a response will still be returned.

The Answer model should include the following:

    id

    question

    answer

Video Summary

Create a 1 to 3 minute video summary of your project that meets the following requirements:

    The video should be created in MP4 format.

    The video should include screen-capture recordings to highlight the sections of the project that are important in meeting the project requirements.

Grading Requirements

For this project, your grade will consist of a combination of general setup and format requirements and your actual code. Refer to the following criteria for more detailed information.
General Setup and Format with Video Summary: 10%

    Your project must be created in an IntelliJ project called Summative-1-Lastname-Firstname.

    Your project must be built using Spring Boot and Spring MVC.
        Initialize the project using start.spring.io.

    Your project must have a series of tests using MockMvc.

    Your project must use in-memory data that follows the pattern demonstrated previously in this module.

    Your REST API must accept and return data in JSON format where appropriate.

    Your REST API must be documented using Swagger.
        Save the .yaml file in the root of the project directory.

    You must provide a 1 to 3 minute video summary of the project.

Quote API: 30%

    The code is clean. (It follows general patterns as presented in class.)

    The Quote API provides a quote of the day service and must implement the following route:

        URI: /quote

        Method: GET

        Request Body: None

        Response Body: Quote

    The Quote model should include the following:

        id

        author

        quote

    Your service must contain at least 10 quotes.

    The quotes must be served up at random.

    You must use MockMvc to test Quote API.

Word API: 30%

    The code is clean. (It Follows general patterns as presented in class.)

    The Word API provides a word of the day service and must implement the following route:

        URI: /word

        Method: GET

        Request Body: None

        Response Body: Definition

    The Definition model should include the following:

        id

        word

        definition

    Your service must contain at least 10 words and their corresponding definition.

    The words and definitions must be served at random.

    You must use MockMvc to test Word API.

Magic 8 Ball API: 30%

    The code is clean. (It follows general patterns as presented in class.)

    The Magic 8 Ball API provides a magic 8 ball service and must implement the following route:

        URI: /magic

        Method: POST

        Request Body: Question

        Response Body: Answer

        The POST request for the Magic 8 Ball endpoint should include a user-provided question.
    note

    You are not required to include any model validations for this summative project. This means that it is possible to submit the Magic 8 Ball POST request without a question, and a response will still be returned.

    The Answer model should include the following:

        id

        question

        answer

    Your service must contain at least 6 different Magic 8 Ball responses.

    The Magic 8 Ball answers must be served at random.

    You must use MockMvc to test Magic 8 Ball API.

    The POST request should include a user-provided question.
