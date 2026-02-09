# Docusaurus assessment

## Description

This project represents my solution for adding globaly line numbering to code blocks. 

To implement it I have run the command ```npm run swizzle``` and chose CodeBlock from the list of options. It created a folder themes in src directory with index.tsx file. There I have returned CodeBlock component with ```showLineNumbers``` globally. Also, I have implemented a condition by taking metastring from props to hide line numbering in case the developer adds the customed ```hideLineNumbers``` at the code block locally.

## Getting Started
### Deployed version with Vercel - [click here!](https://docusaurus-assessment.vercel.app/)
### Installing
1. **Clone** repository:

```bash 
git clone https://github.com/IamAdri/adrielle.git
```

2. **Install** dependencies:
```bash 
npm install
```


3. **Run** the development server:

```bash
npm start
```

## Author

Adriana Sprincean - **atoma304@gmail.com**

## License

This project is licensed under the MIT License - see the LICENSE file for details.

