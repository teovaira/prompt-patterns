# Exercise 2: Data Extraction Template

## Objective
Extract structured data from unstructured input.

## Template Prompt
"Extract the following fields from the text: Name, Age, Location, Occupation. Return the output in JSON format."

## Test Input 1
**Text**: "John Doe, age 29, lives in Paris and works as a software engineer."

**Output**:
```json
{
  "Name": "John Doe",
  "Age": 29,
  "Location": "Paris",
  "Occupation": "software engineer"
}
```

## Test Input 2
**Text**: "Maria Garcia is 34 years old, she's from Barcelona and her job is marketing manager."

**Output**:
```json
{
  "Name": "Maria Garcia",
  "Age": 34,
  "Location": "Barcelona",
  "Occupation": "marketing manager"
}
```

## Test Input 3
**Text**: "The new employee Alex Chen, 27, moved from Tokyo where he worked as a data analyst."

**Output**:
```json
{
  "Name": "Alex Chen",
  "Age": 27,
  "Location": "Tokyo",
  "Occupation": "data analyst"
}
```

## Validation
The template consistently extracts the four required fields across different text structures and returns properly formatted JSON. The prompt works reliably even when information is presented in different orders or phrasings.