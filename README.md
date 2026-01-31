## Hi there 👋

This is my personal website repository, deployed at [grigore.xyz](https://grigore.xyz).

### 🚀 Deployment

The website is automatically deployed to Firebase Hosting via GitHub Actions when changes are pushed to the `main` branch.

**Setup Requirements:**
1. Create a Firebase project named `grigorexyz`
2. Add the Firebase service account JSON as a GitHub secret: `FIREBASE_SERVICE_ACCOUNT_GRIGOREXYZ`
3. Push to the `main` branch to trigger automatic deployment

**Manual Deployment:**
```bash
# Install Firebase CLI
npm install -g firebase-tools

# Login to Firebase
firebase login

# Deploy to Firebase Hosting
firebase deploy --only hosting
```

### 🛠️ Local Development

```bash
# Serve locally with Python
python3 -m http.server 8000

# Or use Firebase emulator
firebase serve
```

<!--
**grigorexyz/grigorexyz** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I'm currently working on ...
- 🌱 I'm currently learning ...
- 👯 I'm looking to collaborate on ...
- 🤔 I'm looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
