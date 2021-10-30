# react-native-3d-button

Download and include Button.js file your project.

Import Button component in App.js:

```
import Button from './src/components/Button'
```
And add the component as below:
```
{/* RED BUTTON */}

<Button
  text="Click"
  buttonCustomStyles={{
    backgroundColor: "#FF50505",
    borderRadius: 2
  }}
  textCustomStyles={{
    color: "#FFF"
  }}
  onClick={() => { alert("Clicked!") 
/>

{/* BLUE BUTTON */}

<Button
  text="Click"
  buttonCustomStyles={{
    backgroundColor: "#6495ED",
    borderRadius: 8,
    marginTop: 10
  }}
  textCustomStyles={{
    color: "#FFF"
  }}
  onClick={() => { alert("Clicked!") 
/>

{/* DARK BUTTON */}

<Button
  text="Click"
  buttonCustomStyles={{
    backgroundColor: "#505050",
    borderRadius: 15,
    marginTop: 10
  }}
  textCustomStyles={{
    color: "#FFF"
  }}
  onClick={() => { alert("Clicked!") 
/>

{/* ORANGE BUTTON */}

<Button
  text="Click"
  buttonCustomStyles={{
    backgroundColor: "#FFBF00",
    borderRadius: 50,
    marginTop: 10
  }}
  textCustomStyles={{
    color: "#505050"
  }}
  onClick={() => { alert("Clicked!") 
/>
```

<img src="https://user-images.githubusercontent.com/41868006/139531179-b68baf6b-6ed0-4fd1-9977-15e945dca312.png" width="50%" />
