# 🚦PLC - Traffic Light 

- In this project a traffic light controller in CODESYS is implemented. 

- A state machine cycles through the different signal phases of a traffic light

- the program is written in Structured Text (ST) and uses PLC timers 


**For code access or questions, please contact me**



# Technologies used

- Development Environment - CODESYS V3

- Programming Language - Structured Text (ST)



# How it works 

- State Logic — The controller cycles through RED → RED‑YELLOW → GREEN → YELLOW → RED.

- Timer Control — Each state is active for a configurable duration using PLC timers.

- Variables — Boolean variables represent the lamp outputs (red, yellow, green).



```mermaid

flowchart LR

A[red] --> B[red-yellow] 
B --> C[green] 
C --> D[yellow]
D --> A

style A fill:#ff4d4d,stroke:#b30000,stroke-width:2px,color:#000000
style B fill:#ffcc66,stroke:#cc9900,stroke-width:2px,color:#000000
style C fill:#66cc66,stroke:#339933,stroke-width:2px,color:#000000
style D fill:#ffeb3b,stroke:#b3a300,stroke-width:2px,color:#000000

```

<br>
<br>

# Result


![Traffic Light Demo](traffic_light.gif)


