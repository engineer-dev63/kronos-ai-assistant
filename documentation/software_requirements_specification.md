# Software Requirements Specification (SRS)

## 1. Introduction

### 1.1 Purpose

The purpose of this document is to **provide a detailed specification of all functional, non-functional, and interface requirements** for the **(Kronos AI)** system, as well as to document its **business rules** and define its **general infrastructure** guidelines.

### 1.2 Scope

Kronos AI is a web platform that provides an intuitive interface for conversing with generative Artificial Intelligence models.

## 2. General Description


### 2.1  Requisitos


### Functional Requirements

| ID | Requirement |
| --- | --- |

| RF01 | The system must allow users to register by providing their name, email, username, and password. |

| RF02 | The system must allow users to log in using their email or username and password. |

| RF03 | The system must allow users to request password recovery via email. |

| RF04 | The system must allow users to create new conversations with the assistant. |

| RF05 | The system must allow users to send text messages to the assistant. |

| RF06 | The system must send user messages to the Groq API for processing and receive the generated response. |

| RF07 | The system must display the assistant's responses without reloading the page. |

| RF08 | The system must store the conversations conducted by the user. |

| RF09 | The system must allow users to view and resume previous conversations. |

| RF10 | The system must allow users to delete and favorite their conversations. |

| RF11 | The system must allow users to define how they want to be addressed by the assistant. |

| RF12 | The system must allow users to set custom instructions for the assistant. |

| RF13 | The system must allow users to customize the interface theme and wallpaper. |

| RF14 | The system must allow users to send voice messages. |

| RF15 | The system must transcribe the user's voice messages and display the text in the conversation. |

| RF16 | The system must allow users to receive audio responses from the assistant. |

| RF17 | The system must allow users to choose between automatic audio responses or text-only responses. |

| RF18 | The system must allow users to individually convert an assistant's response into audio. |

### Non-Functional Requirements

| ID | Requirement |
| --- | --- |

| RNF01 | The system must be developed using HTML, CSS, and JavaScript on the frontend. |

| RNF02 | The system must use Python and Django on the backend. |


| RNF03 | The system must use MySQL for data storage. |

| RNF04 | The system must use the Groq API for message processing. |

| RNF05 | Communication between the frontend and backend must occur 

asynchronously. |

| RNF06 | The Groq API access key must not be exposed to the frontend. |

| RNF07 | User passwords must be stored using secure encryption/hashing mechanisms. |

| RNF08 | The system must ensure that each user only has access to their own data and conversations. |

| RNF09 | The interface must be responsive and suitable for different screen sizes. |

| RNF10 | The system must implement appropriate error handling during its utilization. |



## 2.2 Infrastructure

* **Frontend:** HTML, CSS, JavaScript

* **Backend / Server-Side:** Python, Django

* **AI Model API:** Groq AI

* **Database:** MySQL