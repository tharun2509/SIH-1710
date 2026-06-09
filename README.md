# Smart India Hackathon Workshop
# Date:9/6/25
## Register Number:212225240172
## Name:THARUN DP
## Problem Title
SIH 1710: Enhancing Navigation for Railway Station Facilities and Locations
## Problem Description
Background: Railway stations are complex environments with numerous facilities and locations such as ticket counters, platforms, restrooms, food courts, and waiting areas. Passengers often face difficulties in navigating these spaces, especially in large or unfamiliar stations. Efficient and user-friendly navigation systems are crucial for improving passenger experience, reducing congestion, and ensuring timely travel connections. Description: The problem involves developing a comprehensive navigation solution for railway stations that assists passengers in locating various facilities and destinations within the station premises. This includes creating detailed maps, providing real-time directions, and integrating features such as accessibility options for individuals with disabilities. The solution should be intuitive, easy to use, and accessible via multiple platforms, including mobile devices and digital kiosks. Key challenges include updating navigation information in real-time, ensuring accuracy, and accommodating the diverse needs of all passengers. Expected Solution: The expected solution is a multi-platform navigation system that provides detailed, real-time directions to all facilities and locations within a railway station. This system should include: A mobile application with 3D interactive maps and step-by-step navigation. Digital kiosks located throughout the station with touch-screen interfaces. Voice-guided navigation for visually impaired passengers. Regular updates to reflect changes in station layout and facility locations. Integration with existing railway apps and services for seamless user experience. The solution should enhance the overall passenger experience by reducing confusion, saving time, and improving accessibility within the station.

## Problem Creater's Organization
Ministry of Railway

## Idea
RailNav AI – An intelligent indoor navigation system for railway stations that helps passengers locate platforms, ticket counters, restrooms, food courts, waiting halls, elevators, and other facilities through real-time navigation.

The system combines:

Interactive 3D station maps
AI-powered route guidance
QR code-based positioning
Voice assistance for visually impaired users
Digital kiosk support
Real-time facility updates

## Proposed Solution / Architecture Diagram
Passengers often struggle to find facilities in large railway stations. Our solution provides accurate indoor navigation similar to Google Maps but specifically designed for railway stations.

Key Features
1. Interactive 3D Map
Complete station visualization
Zoom and rotate functionality
Platform and facility highlights
2. Smart Route Guidance
Shortest path calculation
Escalator/elevator preferences
Congestion-aware routing
3. Voice Navigation
Speech-based directions
Multiple language support
Accessibility support for visually impaired users
4. QR-Based Indoor Positioning
QR codes installed across station premises
User scans nearest QR to identify current location
Low-cost alternative to GPS indoors
5. Digital Kiosks
Touch-screen information points
Route printing option
Emergency assistance
6. Real-Time Updates
Facility maintenance alerts
Temporary route closures
Platform changes

<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/b61a9005-a9b8-44e6-8aab-4ddd37355dcb" />

## Use Cases
Passenger Navigation
User enters destination.
App displays shortest route.
Platform Finding
Passenger finds correct platform quickly.
Facility Search
Locate restroom, ATM, food court, waiting room.
Accessibility Support
Wheelchair-friendly route suggestions.
Voice guidance for visually impaired users.
Emergency Navigation
Fastest path to exits or medical centers.
Tourist Assistance
Multi-language navigation support.

## Technology Stack

Frontend
React Native (Mobile App)
React.js (Admin Dashboard)
Three.js (3D Maps)
Backend
Node.js
Express.js
Database
MongoDB
Navigation Engine
Graph-based mapping
A* Pathfinding Algorithm
AI Features
OpenAI API / Local LLM
Speech-to-Text
Text-to-Speech
Mapping
Three.js
Mapbox SDK
Authentication
JWT
Railway User Login
## Dependencies
Frontend
npm install react-native
npm install react-navigation
npm install three
npm install axios
npm install react-native-voice
npm install react-native-tts
Backend
npm install express
npm install mongoose
npm install cors
npm install dotenv
npm install jsonwebtoken
AI & Navigation
npm install openai
npm install pathfinding
