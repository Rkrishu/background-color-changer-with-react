# Background-color-changer-with-react
Recently i started learn react.js and i complete the all topics of react like, npm, npx, use of creat-react-app, props, hooks, etc. 
so i decided to start creating a projects and i creat my first project a background color changer app with uing react.js its a very small projet.

# code

import { useState } from "react";
function App() {
  const [color, setColor] = useState("black");
  return (
    <div
      className="w-full h-screen duration-200"
      style={{ backgroundColor: color }}
    >
      <div
        className="fixed flex flex-wrap
        justify-center bottom-20 inste-x-0 px-2"
      >
        <div
          className="flex flex-wrap justify-center
          gap-5 shadow-lg bg-white px-3 py-2 rounded-3xl"
        >
          <button
           onClick={() => setColor("red")}
            className="outline-none px-4 py-1
          rounded-full text-white shadow-lg"
            style={{ backgroundColor: "red" }}
          >
            red
          </button>

          <button
           onClick={() => setColor("green")}
            className="outline-none px-4 py-1
          rounded-full text-white shadow-lg"
            style={{ backgroundColor: "green" }}
          >
            green
          </button>

          <button
           onClick={() => setColor("yellow")}
            className="outline-none px-4 py-1
          rounded-full text-white shadow-lg"
            style={{ backgroundColor: "yellow" }}
          >
            yellow
          </button>

          <button
           onClick={() => setColor("pink")}
            className="outline-none px-4 py-1
          rounded-full text-white shadow-lg"
            style={{ backgroundColor: "pink" }}
          >
            pink
          </button>

          <button
           onClick={() => setColor("orange")}
            className="outline-none px-4 py-1
          rounded-full text-white shadow-lg"
            style={{ backgroundColor: "orange" }}
          >
            orange
          </button>

          <button
           onClick={() => setColor("blue")}
            className="outline-none px-4 py-1
          rounded-full text-white shadow-lg"
            style={{ backgroundColor: "blue" }}
          >
            blue
          </button>

          <button
            onClick={() => setColor("brown")}
            className="outline-none px-4 py-1
          rounded-full text-white shadow-lg"
            style={{ backgroundColor: "brown" }}
          >
            brown
          </button>

          <button
            onClick={() => setColor("olive")}
            className="outline-none px-4 py-1
           rounded-full text-white shadow-lg"
            style={{ backgroundColor: "olive" }}
          >
            olive
          </button>

          <button
           onClick={() => setColor("black")}
            className="outline-none px-4 py-1
            rounded-full text-white shadow-lg"
            style={{ backgroundColor: "black" }}
          >
            black
          </button>
        </div>
      </div>
    </div>
  );
}

export default App;
