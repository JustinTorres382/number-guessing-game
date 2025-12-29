# number-guessing-game
The program generates a random number between 1 and 100 and the user needs to guess that number.

## User Interface
<img width="441" height="361" alt="Number-Guessing-Game drawio" src="https://github.com/user-attachments/assets/03a752eb-226b-428e-b851-cec3d21a4f3c" />

## Functions
User Input
```typescript
function UserInput() {
  return {
    </input>
  }
}
```

Submit Button
```typescript
function SubmitButton() {
  return {
    <button onclick={generateRandomNumber}>
      Submit
    </button>
  }
}
```

Generate Number
```typescript
function generateRandomNumber() {
  return (
    Math.floor(Math.random() * 101);
  );
}
```
