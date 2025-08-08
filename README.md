What I Built
I set out to build a fun, interactive web application called the "On-demand Coloring Page Creator." The app allows a user to type in any theme (like "dinosaurs" or "space adventure"), and using AI, it generates a unique, black-and-white, line-art coloring page ready to be printed or saved.
 I used a two-step conversational process in Google AI Studio to create the app:

The Initial Prompt:
"Create a web application called 'Coloring Page Creator'. The design must be clean and user-friendly. The app needs a main title, a text input field for a theme with the placeholder text 'What do you want to color today?', and a primary button that says 'Generate Page'. When the button is clicked, it must call an image generation API to create a 'black and white, minimalist, clean line-art, coloring book page' based on the user's theme. While generating, show a 'Loading...' message. Then, display the generated image."

The Refinement Prompt: I then used the iterative chat feature to improve the user experience with this follow-up prompt:
"Great. Now add three example buttons under the text input with the themes 'Fantasy Forest', 'Ocean Life', and 'Space Adventure'. Clicking a button should fill the text input with that theme."
Demo