# DataQueryEngine

**DataQueryEngine** is a dynamic and evolving library of SQL queries designed to support the AI Agent in interacting with **QuestDB** for real-time data retrieval. The library contains a collection of predefined queries, each associated with a corresponding prompt that allows the AI Agent to build and execute SQL queries efficiently and accurately.

With **DataQueryEngine**, the AI Agent learns from user interactions, adding validated and approved queries to the library, ensuring it grows smarter and more versatile over time.

## Features

- **Dynamic Query Generation**: The AI Agent can generate SQL queries based on user input by leveraging the prompts in the library.
- **User Validation**: After query generation, the user validates and refines queries before they are added to the library, ensuring the highest quality.
- **Extensible Library**: The library grows automatically as more queries are validated by users, expanding the query set to handle more complex or diverse requests.
- **Real-time Integration**: Queries are executed in real-time against **QuestDB**, ensuring up-to-date and accurate results.

## Getting Started

### Prerequisites

- **QuestDB**: This library is designed to work seamlessly with QuestDB, a high-performance time-series database.
- **AI Agent**: This repository is integrated into the AI Agent Lab, where queries are built dynamically based on user prompts.



## Using DataQueryEngine

1. Define Queries: Add predefined SQL queries to the queries/ directory. Each query should correspond to a prompt that guides the AI Agent in understanding what data the query retrieves.

2. Validate Queries: After the AI Agent generates a query based on user input, show it to the user for validation. If the user approves, the query is added to the library.

3. Expand the Library: As users validate new queries, the library grows and becomes more capable, allowing the AI Agent to handle an increasing variety of requests.

4. Integrate with AI Agent: Connect this query library to the AI Agent, enabling it to use the DataQueryEngine library for dynamic query generation and execution.


## Query Validation Flow

1. The AI Agent generates a query based on the user input.
2. The query is presented to the user for validation.
3. If the user approves, the query is added to the library.
4. The validated query is stored for future use.
