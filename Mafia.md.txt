# Conversation
- conversationId: 6119d62d-f702-49ba-9038-c11dc1fc8ac2
- endpoint: azureOpenAI
- title: New Chat
- exportAt: 11:05:05 GMT-0500 (Eastern Standard Time)

## Options
- presetId: null
- model: gpt-4.1
- modelLabel: OpenAI GPT-4.1
- resendFiles: true
- iconURL: openAI
- spec: Azure OpenAI GPT-4.1
- endpoint: azureOpenAI
- endpointType: undefined
- title: New Chat

## History
**User**
Tell me rule for Mafia game with Doctor, detective, bomber. Doctor can save 2 times only total. Bonber is a separate player who wins if they are lynched but not killed in night


**OpenAI GPT-4.1**
Here is a set of rules for **Mafia** with the following roles: **Doctor**, **Detective**, **Bomber**, and standard **Mafia/Citizen** roles. These rules are written for a group with at least 6 players.

---

## **Mafia Game Rules with Doctor (2 Saves), Detective, Bomber**

### **Roles**
- **Mafia**: Kills one player per night. Mafia wins if their numbers equal citizens at any time.
- **Citizen**: No special power. Citizens win by eliminating all Mafia.
- **Doctor**: Can choose one player to save from night kill, but can use this ability only **twice in the game** (max total 2 saves; cannot save the same person twice in a row).
- **Detective**: Each night, can check if a player is Mafia (receives Yes/No answer).
- **Bomber**: Wins if **lynched during the day**. If killed by the Mafia at night, they lose. Bomber is a separate faction.

### **Setup**
- Moderator assigns roles secretly.
- Players close eyes at night and open during the day.

### **Game Flow**

#### **Night Phase**
1. **Mafia** decides on a target to kill.
2. **Doctor** chooses whom to save (if Doctor still has saves remaining).
3. **Detective** investigates one player (Moderator tells "Mafia" or "Not Mafia").
4. Moderator resolves actions: If Doctor saves the Mafia's target, that target survives.

#### **Day Phase**
1. Moderator announces who, if anyone, died during the night.
2. All players discuss ("accuse," "defend," etc.).
3. Voting takes place for lynching one player.
    - If **Bomber** is lynched, they instantly win and game ends.
    - If another player is lynched, reveal their role and remove them.

#### **Win Conditions**
- **Citizens** win when all Mafia are eliminated.
- **Mafia** win if they equal or outnumber citizens at any time.
- **Bomber** wins **instantly** and game ends if lynched during day (not if killed at night).

---

### **Special Notes**
- Doctor can save **himself** but not twice in a row.
- Doctor cannot use both saves in the same night.
- Bomber is a standalone role: not Mafia or Citizen; cannot be killed by lynching at night. If Mafia targets Bomber, Bomber loses.
- If Bomber is lynched **and** night kill happens on same round (with simultaneous resolution), resolve the lynch first; Bomber wins.

---

## **Summary Table**

| Role      | Night Power         | Win Condition                |
|-----------|--------------------|-----------------------------|
| Mafia     | Kill (night)       | Mafia number >= Citizen     |
| Citizen   | None               | All Mafia dead              |
| Doctor    | Save (2 total)     | Citizens win                |
| Detective | Investigate (night)| Citizens win                |
| Bomber    | None               | Lynched (day)               |

---

If you want these rules in a specific format (like LaTeX), let me know!


