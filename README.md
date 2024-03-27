# Isaac Acosta, Cayden Haas, Eddie Brito
# CSCI 428
# Night Owls

Topic: Zero Trust Management

Zero Trust Management is a strategic approach to cybersecurity that operates on the principle "never trust, always verify." This model dictates that no entity inside or outside the network is trusted by default, and verification is required from everyone trying to access resources on the network. This concept is becoming increasingly important as organizations face cyber threats and traditional security models fall short.

Design:

Focuses on strict access controls and verification processes.

-   Least Privilege Access: Ensuring that users and systems have only the minimum level of access necessary to perform their tasks.

-   Micro-segmentation: Dividing the network into small, secure zones to control traffic flow and limit access.

-   Multi-factor Authentication (MFA): Implementing multiple layers of authentication to verify the identity of users and devices.

-   Continuous Monitoring and Validation: Regularly verifying the security posture of all devices and endpoints.

In Java, there is a library called Spring Security; its architecture could leverage authentication and authorization and microservices to create isolated and secure zones. Each service is a gatekeeper, ensuring access is granted only after rigorous authentication and authorization.

Idea:

Our core idea revolves around creating a Java-based application that embodies the Zero Trust principles. This application could be a web service or an application where access to different services requires passing through multiple layers of security checks. The application will use Java's security frameworks and libraries to implement features like MFA, encryption, and secure API gateways.

Challenges/Problems:

1.  Adopting a zero-trust architecture requires a significant overhaul of existing systems, which can be complex and resource-intensive when trying to implement.

2.  Ensuring compatibility and integrating Zero Trust principles with older legacy systems can pose significant challenges.

3.  The multiple security checks and encryption layers can introduce latency, affecting the system's performance.

4.  Balancing security with user convenience is critical. Overly stringent security measures can hinder user experience and productivity.

