## System-1 Description
System-1 gives to User a set of services from different providers.

# Available User types:
| User-Type | Time limit | Operations limit
| ------ | ------ | ------ |
| Guest |20 minutes | 5 in 24 hours, 20 in 7 days |
| Basic | 50 minutes | 50 in 7 days |
| Company | Unlimited | Unlimited |
| Advanced | Unlimited | Unlimited |

> Note: after finish the time limit, the guest switches type to the *idle*

Available transitions between User-Types:
   * "Guest” → “Basic” → “Advanced” 
   * “Advanced” → “Basic” → “Guest”
   * “Company” → “Advanced”
   * “Advanced” →  “Company”

![Class Diagram](/class_diagram_system-1.jpg)