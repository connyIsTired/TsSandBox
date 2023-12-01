# TsSandBox
Sandbox for messing around with TypeScript

Write code in the src folder and do cool and interesting TypeScript stuff. Then run `npm run givr` to compile and run your super awesome code. If it doesn't work please feel free to assume this little sandbox
I built is busted as hell. It has got to be someones fault your code doens't run. It might as well be mine. Either way, I am proud of you. 

## npm scripts that might be useful

**compile** - it compiles TypeScript to JavaScript. Neat!

**givr** - ya know, like ya better giv'r Ricky if ur gonna jump your dirtbike over that creek. (Compiles your TS from the src file into a dist file and runs the dist/index.js file)

**adhoc** - compiles the TS files from src into dist and runs a particular one. Tell npm which one by passing the file name to the file argument. Ex: `npm run adhoc --file=specialFile.js`

**clean** - runs rimraf so that windows OS computers can clean and remove the dist folder. Don't worry, when you compile your TS again the dist folder should go back. I think...
