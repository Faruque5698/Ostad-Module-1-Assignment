# Part A: Theoretical Questions

## 1. What is DevOps Engineering?

### Answer
DevOps means Development and Operations.

It is a way where developers and operations teams work together. The goal is to make software development, testing, and deployment faster and more reliable.

In traditional systems, developers write code and operations teams handle servers separately. In DevOps, both work together and use automation tools to speed up the process.

Example: A developer pushes code to GitHub, and GitHub Actions automatically tests and deploys it to a server.

---

## 2. How does DevOps fit into the SDLC?

### Answer
SDLC means Software Development Life Cycle. It is the process of creating software step by step.

DevOps adds value in many phases, including:

1. Development: Developers write and manage code using Git.
2. Testing: Automated testing helps find issues early.
3. Deployment: CI/CD pipelines deploy software quickly and safely.
4. Maintenance: Monitoring and updates keep systems running smoothly.

Example: After code is pushed to GitHub, GitHub Actions can run tests and deploy the application automatically.

---

## 3. What values does a DevOps Engineer bring to an organization?

### Answer
A DevOps Engineer helps a company work faster and more efficiently.

Four important values are:

1. Fast Delivery: Software is released faster with CI/CD.
2. Automation: Repetitive tasks are reduced with scripts and tools.
3. Teamwork: Developers and operations teams collaborate better.
4. Reliability: Systems stay stable and recover quickly from issues.

Example: If one server fails, another server can handle traffic using load balancing.

---

## 4. Why is SWE experience helpful before DevOps?

### Answer
Software Engineering experience helps because DevOps works closely with coding, systems, and applications.

A developer already understands Git, databases, application design, and deployment concepts. This makes it easier to learn DevOps tools like Docker, CI/CD, and server management.

For example, as a Laravel developer, I already know PHP, MySQL, Git, and how web applications work. That makes learning DevOps easier and faster.

---

## 5. Why is networking knowledge important in DevOps?

### Answer
Networking knowledge is important because DevOps engineers work with servers, websites, and cloud systems.

Important topics include:

- DNS: Converts domain names into IP addresses.
- IP Address: Identifies a device or server on a network.
- Ports: Used for different services.
  - Port 80 = HTTP
  - Port 443 = HTTPS
  - Port 22 = SSH
- Protocols: Rules for communication such as HTTP, HTTPS, TCP, and SSH.

If a website is not working, a DevOps engineer checks DNS, ports, IPs, and network settings to solve the issue.

---

## 6. What soft skills are essential for a DevOps Engineer?

### Answer
Soft skills are very important in DevOps because engineers work with different teams and solve problems under pressure.

Important soft skills include:

1. Communication
2. Teamwork
3. Problem solving
4. Patience
5. Time management

During incidents, these skills help engineers stay calm, share updates, and fix problems quickly.

Example: If a production website goes down, a DevOps engineer must communicate clearly, check logs, and work with the team to restore service.

---

## 7. Why are patience and troubleshooting important in DevOps?

### Answer
Patience and troubleshooting are essential because systems often fail in unexpected ways.

A DevOps engineer must stay calm, investigate step by step, and find the real cause of the issue.

### Real-life example
Suppose a Laravel app is deployed with Docker, but the website does not open.

The engineer checks:

1. Whether Docker containers are running
2. Docker logs
3. Application logs
4. Network ports
5. Database connection

After checking, the issue is found: the database host name is wrong. After fixing it and restarting the app, the website works again.

This shows why patience and troubleshooting are important in DevOps.
