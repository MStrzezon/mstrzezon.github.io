---
layout: default
title: Socket Poker Game - Multiplayer Card Game
permalink: /projects/poker/
---

# 🃏 Socket Poker Game

**Status**: ✅ Completed  
**Language**: Java  
**Architecture**: Client-Server

---

## 📋 Overview

A sophisticated multi-player poker game implementation featuring real-time socket communication, comprehensive game protocol, and complete Java-based architecture. The project demonstrates advanced object-oriented programming principles and network communication patterns.

---

## 🎯 Key Features

### 🎮 **Complete Poker Gameplay**
- Full 5-card draw poker implementation
- Support for 2-4 players per game
- Real-time betting system with raise, call, fold options
- Comprehensive hand evaluation and ranking system

### 🔗 **Network Architecture**
- Client-server model with socket communication
- Custom communication protocol
- Multi-threaded server handling concurrent players
- Robust error handling and connection management

### 🎛️ **Game Management**
- Game state management across multiple rounds
- Player turn coordination and timing
- Ante system with configurable betting limits
- Real-time game status updates

### 📊 **Advanced Features**
- Card drawing and replacement mechanics
- Game result calculation and ranking
- Player statistics and funds tracking
- Comprehensive command system

---

## 🛠️ Technical Architecture

### **Project Structure**
```
poker/
├── poker-client/     # Client application
├── poker-server/     # Server implementation  
├── poker-common/     # Shared utilities
├── poker-model/      # Game logic and models
├── Javadoc/         # Complete API documentation
└── sonar-cube/      # Code quality reports
```

### **Core Components**

#### **Server Architecture**
```java
// Main server components
- Server.java: Main server management
- ClientHandler.java: Individual client management
- GameProtocol.java: Communication protocol handler
```

#### **Game Logic**
```java
// Game model classes
- Match.java: Game session management
- Player.java: Player state and actions
- Hand.java: Card hand evaluation
- Cards package: Card representation and deck management
```

#### **Client Application**
```java
// Client implementation
- Client.java: Server connection and UI
- Communication handling and user interaction
```

---

## 🚀 Communication Protocol

### **Client Commands**
```
/help          - Display all available commands
/state         - Show current game state
/create {ante} - Create new game (ante: max 10)
/join          - Join existing game
/start         - Start game (minimum 2 players)
/players       - Show player count
/id            - Display your player ID
/money         - Show your current funds
/funds         - Show total table funds
/hand          - Display your cards
/call          - Call current bet
/raise {amount}     - Raise bet by amount
/fold          - Fold current hand
/draw {cards}  - Draw new cards (e.g., /draw 123)
/result        - Show game results
/end           - End current game
```

### **Server Responses**
- Real-time game state updates
- Player action confirmations
- Error messages and validation
- Game progression notifications

---

## 🎲 Game Flow

### **1. Game Setup**
```java
// Game initialization
1. Server starts with max player limit (2-4)
2. Clients connect and receive welcome message
3. Organizer creates game with ante amount
4. Players join until minimum requirement met
```

### **2. Betting Rounds**
```java
// Betting mechanics
1. Each player receives 5 cards
2. Betting round: call, raise, or fold
3. Card drawing phase (optional)
4. Final betting round
5. Hand comparison and winner determination
```

### **3. Game Management**
```java
// State management
- Turn-based player actions
- Bet validation and fund management
- Card distribution and hand evaluation
- Result calculation and display
```

---

## 🧮 Technical Implementation

### **Socket Communication**
```java
// Server socket setup
ServerSocket serverSocket = new ServerSocket(port);
// Client connection handling
while (running) {
    Socket clientSocket = serverSocket.accept();
    new ClientHandler(clientSocket).start();
}
```

### **Multi-threading**
```java
// Concurrent client handling
public class ClientHandler implements Runnable {
    // Individual client communication
    // Game state synchronization
    // Protocol command processing
}
```

### **Game Protocol**
```java
// Command processing
public String processMove(int userId, String move, 
                         List<Integer> parameters) {
    // Parse and validate commands
    // Execute game actions
    // Return appropriate responses
}
```

---

## 📚 Documentation & Quality

### **Comprehensive Documentation**
- **Javadoc**: Complete API documentation for all classes
- **Code Coverage**: SonarCube quality analysis
- **Protocol Specification**: Detailed communication protocol
- **Setup Instructions**: Complete deployment guide

### **Quality Metrics**
- Object-oriented design principles
- Error handling and validation
- Code organization and modularity
- Testing and quality assurance

---

## 🔧 Development Setup

### **Requirements**
- Java 11+ (JDK)
- Maven 3.6+
- Network connectivity for socket communication

### **Build & Run**
```bash
# Build project
mvn clean install

# Start server (max 4 players)
java -jar poker-server-1.0-jar-with-dependencies.jar 4

# Start client
java -jar poker-client-1.0-jar-with-dependencies.jar
```

### **Configuration**
- Server port configuration
- Player limits (2-4 players)
- Ante limits and betting rules
- Connection timeout settings

---

## 📈 Project Highlights

### **Technical Skills Demonstrated**
- **Network Programming**: Socket communication and protocols
- **Concurrency**: Multi-threaded server architecture
- **OOP Design**: Clean class hierarchy and encapsulation
- **Game Logic**: Complex state management and rule implementation

### **Software Engineering Practices**
- **Documentation**: Comprehensive Javadoc and protocol specs
- **Testing**: Unit tests and integration validation
- **Quality**: SonarCube analysis and code standards
- **Architecture**: Modular design with separated concerns

---

## 🔗 Links

- **[GitHub Repository](https://github.com/mstrzezon/Poker)** - Complete source code
- **[Javadoc Documentation](https://github.com/mstrzezon/Poker/tree/main/Javadoc)** - API documentation
- **[Protocol Specification](https://github.com/mstrzezon/Poker/blob/main/README.md)** - Communication details

---

## 🏷️ Technologies Used

<div class="tech-showcase">
  <div class="tech-category">
    <h4>Core Technologies</h4>
    <ul>
      <li>Java SE 11+</li>
      <li>Socket Programming</li>
      <li>Multi-threading</li>
      <li>Maven Build System</li>
    </ul>
  </div>
  
  <div class="tech-category">
    <h4>Architecture</h4>
    <ul>
      <li>Client-Server Model</li>
      <li>Custom Protocol Design</li>
      <li>State Management</li>
      <li>Concurrent Programming</li>
    </ul>
  </div>
  
  <div class="tech-category">
    <h4>Quality Assurance</h4>
    <ul>
      <li>Javadoc Documentation</li>
      <li>SonarCube Analysis</li>
      <li>Unit Testing</li>
      <li>Code Coverage</li>
    </ul>
  </div>
</div>

---

*This project showcases advanced Java programming skills, network communication expertise, and game development capabilities with emphasis on clean architecture and comprehensive documentation.*