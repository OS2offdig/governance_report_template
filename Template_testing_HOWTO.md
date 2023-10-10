# 🔎 How to test
### Visually testing a github form based template

1. Locate the template in the .github folder in the root of the branch you wish test.
2. Copy the YAML code into the clipboard
3. Open the test site: https://issue-forms-creator.netlify.app/
4. Press the "+" sign in the upper right corner and choose the option "Paste yaml content"


The YAML will be auto loaded into the test page from the clipboard, and you can proceed to verify that the form looks and works like expected.
<details>

<summary> 🎞️ See the UI workflow here </summary>

![Adding template yaml](Add_template_yaml.gif)

</details>


### ⚠️ Troubleshooting
If nothing happends when pressing the "Paste yaml content" button, your clipboard contains somthing else than a valid yaml, try to copy the form yaml again.

### ❔ FAQ
Q: Whats all the fuss about? Isnt it just at YAML file?

A: Yup, if the tester prefers to test on the raw YAML, this is fine. It is a bit hard to catch visual rendering bugs though

--

Q: Why cant i just test directly in Github?

A: The template is located in the .github folder of the branch containing the suggested changes, this is standard github flow practise, but there is no built in function in Github to render form templates located in a branch, graphically.
