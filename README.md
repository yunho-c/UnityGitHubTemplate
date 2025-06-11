> Source: https://thoughtbot.com/blog/how-to-git-with-unity#2-configure-unity-for-version-control

With your project open in the Unity editor:

- Open the editor settings window.
  - `Edit > Project Settings > Editor`
- Make .meta files visible to avoid broken object references.
    - `Version Control / Mode: “Visible Meta Files”`
- Use plain text serialization to avoid unresolvable merge conflicts.
    - `Asset Serialization / Mode: “Force Text”`
- Save your changes.
    - `File > Save Project`
