## **📖 API – Complete Study Material**

### **1. What is an API?**

**API** stands for **Application Programming Interface**.
It is a **set of rules, protocols, and tools** that allow one software application to communicate with another.

**Think of it like:**
A **restaurant menu** – The menu lists dishes you can order (the functionality). The kitchen is the backend system that prepares it. You don’t need to know *how* the food is cooked, you just place the order via the waiter (API).

---

### **2. Why are APIs Important?**

APIs make software modular and connected. They allow:

1. **Data Sharing** – Between different systems (e.g., a weather app fetching data from a weather API).
2. **Faster Development** – Developers reuse existing functionality instead of building from scratch.
3. **Integration** – Connects different apps, devices, or services (e.g., payment gateway in an e-commerce site).
4. **Automation** – APIs can trigger actions without manual work (e.g., sending SMS notifications automatically).

---

### **3. Real-World Examples**

* **Google Maps API** – Apps can embed maps without building their own map engine.
* **PayPal API** – Enables online payments from websites/apps.
* **Twitter API** – Lets other apps fetch tweets or post on Twitter.
* **Weather API** – Fetches live weather data for apps.

---

### **4. Types of APIs**

#### **(a) Internal APIs** (Private APIs)

* Used **within an organization only**.
* Improves efficiency and modularity of large systems.
* Example: A company’s HR system API for payroll data.

#### **(b) External APIs** (Open APIs / Public APIs)

* Available for **public use** by developers outside the organization.
* Example: Google Maps API, OpenWeather API.

#### **(c) Partner APIs**

* Shared between **trusted business partners**.
* Requires authentication and agreements.
* Example: Airline company providing booking API to travel agencies.

---

### **5. API Communication Protocols**

APIs define **how** systems exchange data:

* **HTTP / HTTPS** (Most common for Web APIs)
* **SOAP** (XML-based, strict rules)
* **REST** (JSON/XML-based, widely used)
* **GraphQL** (Client specifies exactly what data it needs)
* **gRPC** (Binary protocol for speed)

---

### **6. API Request & Response Cycle**

1. **Client** sends request (with method like GET, POST, PUT, DELETE).
2. **Server** processes request.
3. **Server** sends back a **response** (data + status code).

**Example (REST API):**

```
Request: GET https://api.weather.com/city/London
Response: { "temp": 27, "condition": "Sunny" }
```

---

### **7. HTTP Status Codes in APIs**

Status codes tell you **if the request succeeded or failed**.

#### **1xx – Informational**

* 100 Continue – Request received, continue process.
* 101 Switching Protocols – Changing protocol (e.g., HTTP to WebSocket).

#### **2xx – Success**

* 200 OK – Request successful.
* 201 Created – Resource successfully created.
* 204 No Content – Request successful, no content in response.

#### **3xx – Redirection**

* 301 Moved Permanently – Resource moved to new URL.
* 302 Found – Temporary redirect.
* 304 Not Modified – Cached version is fine.

#### **4xx – Client Errors**

* 400 Bad Request – Invalid request syntax.
* 401 Unauthorized – Authentication needed.
* 403 Forbidden – Access denied.
* 404 Not Found – Resource not found.
* 429 Too Many Requests – Rate limit exceeded.

#### **5xx – Server Errors**

* 500 Internal Server Error – Generic server problem.
* 502 Bad Gateway – Invalid response from upstream server.
* 503 Service Unavailable – Server is overloaded or down.
* 504 Gateway Timeout – Server took too long to respond.

---

### **8. Benefits of Using APIs**

* **Reusability** – Don’t reinvent the wheel.
* **Scalability** – Easy to expand services.
* **Security** – Access control and data filtering.
* **Faster Time-to-Market** – Use existing solutions instead of coding from scratch.

---

### **9. Challenges in API Usage**

* **Security Risks** – If exposed, attackers can misuse it.
* **Versioning** – Breaking changes can disrupt clients.
* **Rate Limits** – APIs often restrict excessive usage.
* **Latency** – Slow response time can impact user experience.

---

### **10. Summary Table**

| Topic            | Key Points                                                              |
| ---------------- | ----------------------------------------------------------------------- |
| **Definition**   | Rules & protocols for communication between software                    |
| **Purpose**      | Data sharing, faster development, integration                           |
| **Types**        | Internal, External, Partner                                             |
| **Protocols**    | REST, SOAP, GraphQL, gRPC                                               |
| **Status Codes** | 1xx Info, 2xx Success, 3xx Redirect, 4xx Client Error, 5xx Server Error |
