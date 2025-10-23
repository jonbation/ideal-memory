
<p align = "center"> A simple library that can be used to create branded sign-in,sign-up, and "continue with" buttons. </p>

# Identity Memory
Identity Memory for compose is a library that contains stylized buttons according to the specification of each brand. It allows you to create high quality social sign-in, sign-up, and "continue with" buttons. For example, you can create a Google branded button with a label that displays "Sign up with Google". Just tell the library which brand and variant is required. The library takes care of creating a button with the required brand colors and logo. In addition, it takes care of setting the appropriate semantic properties. This ensures that **the button works well with accessibility services out of the box.** Separate artifacts are available for both material 2 and material 3. 

## Accessibility
As mentioned, the buttons contain appropriate semantic properties that works well with accessibility services. For example, if a user is using the Talkback service and the UI presents one or more of the buttons from this library the talkback service will use the phrase - "{The label of the button} button". For example, if the label is set to "Sign in with Google", the talkback service will say "Sign in with Google button".

