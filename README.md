**Task File Manager (Node.js)**
A simple file-based task creator built using Node.js, initialized with npx, and run using Nodemon. This project allows users to create, edit, rename, and delete .txt files dynamically — simulating a basic task management system using the local file system.

🚀 Features
📝 Create .txt files with a custom filename.

✏️ Edit content inside existing .txt files.

🔁 Rename any file to a new name.

❌ Delete files you no longer need.

🔄 Automatic server reload using Nodemon.

🛠️ Tech Stack
Node.js

Nodemon

Built-in Node.js fs module

📦 Installation & Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
Install dependencies:

nginx
Copy
Edit
npm install
Run the application with Nodemon:

nginx
Copy
Edit
npx nodemon index.js
Replace index.js with your actual main file if different.

How it works:

Enter a filename to create a .txt file.

Edit the file’s content using prompts or interface.

Rename the file to a new name.

Delete the file if it's no longer needed.

📁 Folder Structure
pgsql
Copy
Edit
your-project/
├── node_modules/
├── index.js         # Main application logic
├── package.json
└── README.md
