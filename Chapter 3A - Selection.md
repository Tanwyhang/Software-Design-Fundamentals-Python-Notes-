Here is the summary of the Problem Solving with Flowchart notes formatted as requested:

# Problem Solving with Flowchart

## Solution Design vs Coding
- Design and analysis are crucial before coding to minimize costs
- The Waterfall and Prototype models are popular SDLC approaches 
- Defects cost exponentially more to fix in later stages
- Thoroughly testing design outputs is critical to save time and effort

## Flowcharts
- Flowcharts are visual representations of algorithms and processes
- They use standard symbols:
    <pre>
    Start/End  Input/Output  Process  Decision  Connector
    </pre>
- Flowcharts aid in analyzing, designing, documenting and managing workflows

## Control Structures
Algorithms utilize three fundamental control structures:

1. Sequence
   - Steps are executed linearly, one after another
2. Selection 
   - Execution branches based on a decision or condition  
    <pre>
             Condition
          ┌───────┴────────┐
          │                │ 
        [Yes]            [No]
          │                │
      Statement        Statement 
    </pre>
3. Loop
   - A block of code is repeated while a condition remains true
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
   - Input Celsius temperature
   - Calculate: `fahrenheit = (9/5) * celsius + 32`
   - Output Fahrenheit temperature

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

3. Movie Ticket Price Calculation
   - Decide price based on multiple criteria: age, showtime, membership
   - Apply relevant discounts for members  
   - Display welcome message for foreign customers

Feel free to ask any clarifying questions! I'm happy to explain further.
