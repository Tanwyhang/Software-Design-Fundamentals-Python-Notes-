Here is a concise summary of the key points from the Problem Solving with Flowchart notes in markdown format:

# Problem Solving with Flowchart

## Solution Design vs Coding
- Design and analysis are important before coding to reduce costs
- The Waterfall and Prototype models are common SDLC approaches 
- Defects are much costlier to fix in later development stages
- Thorough testing of design outputs saves time and effort

## Flowcharts
- Flowcharts visually represent algorithms and processes
- Use standard symbols:
    ```
    Start/End  Input/Output  Process  Decision  Connector  
    ```
- Help analyze, design, document and manage workflows

## Control Structures
Three key control structures:

1. Sequence 
   - Linear execution of steps
2. Selection
   - Conditional branching based on decisions
    <pre>
             Condition
          ┌───────┴────────┐
          │                │
        [Yes]            [No]
          │                │
      Statement        Statement
    </pre>
3. Loop
   - Repeated execution while a condition is true  
    <pre>
         Condition
            │
           [No]
            │
        Statement
            │
          [Yes]
            │
    </pre>

## Problem Solving Examples 
1. Celsius to Fahrenheit Conversion
   - Input Celsius temp
   - `fahrenheit = (9/5) * celsius + 32` 
   - Output Fahrenheit temp

2. Number Classification
    ```mermaid
    graph TD
        A[Start] --> B[Read number]
        B --> C{number > 0?}
        C -->|Yes| D[Print Positive]
        C -->|No| E{number = 0?}
        E -->|Yes| F[Print Zero] 
        E -->|No| G[Print Negative]
        D --> H[End]
        F --> H
        G --> H
    ```

3. Ticket Price Calculation
   - Multiple selection based on age, showtime, membership 
   - Discounts for members
   - Welcome message for foreigners

Let me know if you have any other questions!
