flowchart TD
    A[Start] --> B[Initialize]
    B --> C[number = 2]
    C --> D[i = 1]
    D --> E{Is i <= 10?}
    E -- Yes --> F[result = number * i]
    F --> G[Print number + " x " + i + " = " + result]
    G --> H[i = i + 1]
    H --> D
    E -- No --> I[End]
