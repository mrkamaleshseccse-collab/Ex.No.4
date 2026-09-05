# Ex.No.4 – Generate and Evaluate Prompts Using Advanced Prompting Techniques

**DATE:** 07/08/2026
**REGISTER NUMBER:** 212225040164

## AIM

To create and test different advanced prompting techniques, compare their responses using different AI tools, and evaluate their performance using a rubric-based method.

The prompting techniques covered in this experiment are:

1. Zero-shot Prompting
2. Few-shot Prompting
3. Chain-of-Thought Prompting
4. Persona Pattern
5. Reverse Prompting
6. Graph Prompting
7. Active Prompting

---

# USE CASE: AI-BASED DRONE NAVIGATION

## SCENARIO

AI-powered autonomous drones are increasingly being used in agriculture, surveillance, emergency response, and delivery services. By combining GPS, cameras, LiDAR, and other sensors, a drone can understand its surroundings, identify obstacles, select suitable routes, and adjust its movement during flight.

## TARGET AUDIENCE

* Artificial Intelligence engineers
* Robotics students
* Drone developers
* Researchers
* Automation companies

## MAIN OBJECTIVES

* Improve the accuracy of autonomous navigation.
* Detect and avoid obstacles during flight.
* Find efficient routes to the destination.
* Reduce unnecessary battery consumption.
* Improve the safety of autonomous operations.

---

# PROMPT DESIGN AND EVALUATION

## 1. ZERO-SHOT PROMPTING

### Prompt

"Describe how an autonomous drone can use artificial intelligence to reach a destination while detecting and avoiding obstacles."

### Expected AI Response

An autonomous drone can combine GPS information with camera, LiDAR, and other sensor data to understand its surroundings. AI algorithms process this information to identify obstacles and determine a suitable route. While flying, the system continuously checks the environment and changes the drone's direction or altitude whenever necessary. This allows the drone to reach its destination safely without requiring continuous human control.

### Observation

The AI generated an appropriate response directly without receiving examples or previous demonstrations.

---

## 2. FEW-SHOT PROMPTING

### Prompt

**Example 1**

Input: An obstacle is detected directly ahead.
Output: Change the flight direction and maintain a safe distance.

**Example 2**

Input: Battery level becomes critically low.
Output: Stop the mission and return to the designated home point.

**Now Answer:**

Input: Strong wind is detected during the mission.

### Expected AI Response

Decrease the drone's speed, stabilize its position using onboard sensors, and consider returning to the home point if the wind becomes too strong for safe operation.

### Observation

The examples helped the AI understand the expected response pattern and produce a consistent answer.

---

## 3. CHAIN-OF-THOUGHT PROMPTING

### Prompt

"A drone needs to transport medical supplies to a remote location. Describe the sequence of actions it should follow to choose a safe route, avoid obstacles, and manage its battery effectively."

### Expected AI Response

1. Obtain the coordinates of the delivery location.
2. Check the available map and environmental information.
3. Collect data from GPS and onboard sensors.
4. Identify stationary and moving obstacles.
5. Generate several possible flight paths.
6. Compare the paths according to distance, safety, and energy requirements.
7. Select the most suitable route.
8. Continuously monitor the surroundings and battery level.
9. Modify the route whenever unexpected obstacles appear.
10. Complete the delivery and follow the required return procedure.

### Observation

The response was arranged in a logical sequence, making the complete navigation process easier to understand.

---

## 4. PERSONA PATTERN

### Prompt

"Act as a professional autonomous-drone engineer and explain how artificial intelligence can make drone navigation safer and more efficient."

### Expected AI Response

From an autonomous-drone engineering perspective, AI allows information from GPS, cameras, LiDAR, and other sensors to be combined in real time. The system can recognize objects, estimate possible risks, and select an efficient flight path. It can also continuously update the route when environmental conditions change. This reduces the need for manual control while improving navigation reliability and battery efficiency.

### Observation

Assigning a professional role encouraged the AI to provide an explanation using the perspective and terminology of a drone engineer.

---

## 5. REVERSE PROMPTING

### Prompt

"The final result is: The drone avoided several moving obstacles, completed its delivery using an efficient route, and safely returned to its starting location. Create a suitable prompt that could produce this result."

### Expected AI Response

"Develop an autonomous drone navigation system that uses AI, GPS, and computer vision to detect moving obstacles, select an energy-efficient and safe route, complete a delivery task, and automatically return to the starting point after the mission."

### Observation

The AI worked backward from the desired output and constructed a prompt containing the requirements needed to generate that type of result.

---

## 6. GRAPH PROMPTING

### Prompt

"Show the complete working process of an AI-based autonomous drone navigation system using a flow diagram."

### Expected AI Response

Start
↓
Enter Destination
↓
Collect GPS & Sensor Information
↓
Analyze Surrounding Environment
↓
Identify Obstacles
↓
Generate Possible Routes
↓
Select Safe & Efficient Route
↓
Begin Flight
↓
Monitor Obstacles, Weather & Battery
↓
Update Route When Required
↓
Reach Destination
↓
Complete Mission

### Observation

Graph prompting represented the navigation process visually, making the sequence and connection between different stages easier to understand.

---

## 7. ACTIVE PROMPTING

### Prompt

"A drone encounters severe rainfall while travelling to its destination. Decide whether it should continue the mission, but first ask questions about any important information that is missing."

### Expected AI Response

Before making a recommendation, the AI should obtain information such as:

* What is the current battery percentage?
* What level of rain can the drone safely operate in?
* How far is the destination?
* Is the drone carrying a sensitive or important payload?
* Is there a safe landing area nearby?

After collecting these details, the system can determine whether continuing the flight is safe. If the weather or battery condition creates a significant risk, the drone should return or land at a suitable safe location.

### Observation

The AI identified missing information before making a decision, allowing the recommendation to be based on more complete conditions.

---

# OUTPUTS FOR EACH PROMPTING TECHNIQUE

## 1. ZERO-SHOT PROMPTING

### Prompt

"Explain how artificial intelligence enables an autonomous drone to navigate through an unfamiliar environment."

### AI Output

An autonomous drone uses AI to process information from GPS, cameras, LiDAR, and other sensors. The collected data helps it recognize objects and understand the surrounding environment. AI algorithms then calculate a suitable route while maintaining a safe distance from obstacles. The drone continuously monitors its surroundings during flight and can modify its path whenever the environment changes.

---

## 2. FEW-SHOT PROMPTING

### Prompt

**Example 1**

Input: A building is detected in the flight path.
Output: Change direction and maintain a safe distance.

**Example 2**

Input: Battery reaches a critical level.
Output: Return automatically to the home location.

**Now Answer:**

Input: Visibility becomes very poor because of fog.

### AI Output

Output: Reduce the flight speed, increase the use of obstacle-detection sensors, and switch to a safer navigation mode. If visibility becomes too poor for reliable navigation, return to the home location.

---

## 3. CHAIN-OF-THOUGHT PROMPTING

### Prompt

"A drone is assigned to deliver emergency supplies to an isolated area. Explain the sequence it should follow to complete the task safely while conserving energy."

### AI Output

**Step 1:** Obtain the destination coordinates.

**Step 2:** Analyze the available map and environmental information.

**Step 3:** Gather real-time GPS and sensor readings.

**Step 4:** Identify possible obstacles along the route.

**Step 5:** Generate different route options.

**Step 6:** Evaluate each route based on safety, distance, and battery requirements.

**Step 7:** Select the most appropriate route.

**Step 8:** Continuously monitor weather, obstacles, and battery status.

**Step 9:** Recalculate the route if unexpected conditions occur.

**Step 10:** Complete the delivery and follow the required return or landing procedure.

---

## 4. PERSONA PATTERN

### Prompt

"Assume you are a senior engineer specializing in autonomous aerial robotics. Explain the role of AI in improving drone navigation."

### AI Output

As an autonomous aerial robotics engineer, I would use AI to combine information from multiple sensors and create a real-time representation of the drone's surroundings. AI can identify obstacles, estimate risks, and calculate efficient flight paths. It can also react to changing weather and environmental conditions without waiting for human instructions. This improves flight safety, reduces unnecessary energy consumption, and increases the reliability of autonomous missions.

---

## 5. REVERSE PROMPTING

### Prompt

"A drone detected moving objects, selected a safe route, delivered its package successfully, and returned to its base with sufficient battery remaining. Generate a prompt that could have produced this outcome."

### AI Output

"Create an AI-driven drone navigation system that uses GPS, computer vision, and onboard sensors to identify moving objects, calculate a safe and energy-efficient route, complete a delivery mission, and return automatically to its base while maintaining sufficient battery capacity."

---

## 6. GRAPH PROMPTING

### Prompt

"Convert the operation of an autonomous AI drone into a simple flowchart."

### AI Output

Start
│
▼
Set Destination
│
▼
Gather GPS & Sensor Data
│
▼
Understand Environment
│
▼
Detect Obstacles
│
▼
Calculate Route
│
▼
Select Best Route
│
▼
Fly Toward Destination
│
▼
Check Battery & Weather
│
▼
Obstacle Detected?
│
├── Yes → Recalculate Route
│
└── No
↓
Reach Destination
↓
Mission Completed

---

## 7. ACTIVE PROMPTING

### Prompt

"Heavy rain begins while an autonomous drone is travelling. Determine whether the flight should continue, but ask for the necessary information before making the final decision."

### AI Output

The AI first requests additional information:

1. What percentage of battery is remaining?
2. What is the drone's weather-resistance rating?
3. How intense is the rainfall?
4. How far away is the destination?
5. Is a safe landing location available?

If the drone is designed for the current weather and has sufficient battery, the mission may continue with appropriate precautions. If the rainfall is severe, visibility is poor, or the battery is insufficient, returning to the base or landing safely would be the better option.

---

# COMPARISON WITH DIFFERENT AI TOOLS

| Prompting Technique | ChatGPT                      | Google Gemini            | Microsoft Copilot           |
| ------------------- | ---------------------------- | ------------------------ | --------------------------- |
| Zero-shot Prompting | Clear and detailed           | Clear and relevant       | Short and understandable    |
| Few-shot Prompting  | Follows examples well        | Consistent output        | Reasonably follows examples |
| Chain-of-Thought    | Well organized               | Logical response         | Basic but useful            |
| Persona Pattern     | Natural expert tone          | Professional explanation | Concise expert-style answer |
| Reverse Prompting   | Strong prompt reconstruction | Good reconstruction      | Moderate reconstruction     |
| Graph Prompting     | Detailed workflow            | Clear workflow           | Simple flow                 |
| Active Prompting    | Asks useful questions        | Good clarification       | Fewer follow-up questions   |

---

# EVALUATION METHOD – RUBRICS

## EVALUATION CRITERIA

| Criteria    | Excellent (5)                         | Good (4)         | Average (3)                 |
| ----------- | ------------------------------------- | ---------------- | --------------------------- |
| Reasoning   | Logical, complete, and well connected | Mostly logical   | Basic reasoning             |
| Accuracy    | Highly accurate and relevant          | Minor issues     | Some inaccuracies           |
| Conciseness | Clear with efficient use of words     | Slightly lengthy | More verbose than necessary |

---

# RUBRIC SCORES

| AI Tool           | Reasoning | Accuracy | Conciseness | Total / 15 |
| ----------------- | --------: | -------: | ----------: | ---------: |
| ChatGPT           |         5 |        5 |           5 |     **15** |
| Google Gemini     |         4 |        5 |           4 |     **13** |
| Microsoft Copilot |         4 |        4 |           4 |     **12** |

---

# RESULT ANALYSIS

ChatGPT produced the strongest overall responses because its answers were well structured, relevant, and detailed without becoming unnecessarily lengthy. Google Gemini also generated technically sound responses and demonstrated good reasoning, although some answers contained additional information. Microsoft Copilot produced concise and easy-to-read responses, but its explanations were generally less detailed than the other two tools.

---

# CONCLUSION

The experiment demonstrated how different prompting techniques can influence the way AI systems generate responses for an autonomous drone navigation application. Zero-shot prompting provided direct answers without examples, while few-shot prompting helped the AI follow a demonstrated pattern. Chain-of-thought prompting organized complex tasks into sequential steps, whereas persona prompting produced responses from a specified professional viewpoint. Reverse prompting worked backward from an expected output, graph prompting represented the workflow visually, and active prompting collected missing information before making a decision. Based on the rubric evaluation, ChatGPT achieved the highest score because of its strong reasoning, accuracy, and concise presentation.

---

# RESULT

The advanced prompting techniques were successfully created and evaluated using an AI-based drone navigation scenario. The comparison showed that different prompting methods are useful for different types of tasks, including explanation, structured reasoning, workflow representation, and decision-making. The rubric-based evaluation demonstrated that selecting a suitable prompting technique can improve the quality, clarity, and usefulness of AI-generated responses. Thus, the experiment successfully achieved its objective of understanding and evaluating advanced prompt engineering techniques for a real-world engineering application.
