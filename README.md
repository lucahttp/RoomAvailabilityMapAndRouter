# Room Availability Map & Router
![image](https://github.com/lucahttp/RoomAvailabilityMapAndRouter/assets/32082555/6e250e96-7ce2-49da-b7ff-e51c22e15bda)



## requirements
    - vscode
    - powerplatform vs code extension
    - windows local admin rights 
## preparation
    inside vs code
        inside the terminal run the following command
            pac pcf init -ns ltc -n RoomAvailabilityMapAndRouter -t dataset -fw react --run-npm-install
            
## reverse - engineering
    pac canvas unpack --sources 'C:\Users\sainluca\OneDrive - Boehringer Ingelheim\UCC CoCo\PCF\PCF-SVG-Control\Samples\SolutionUnpacked' --msapp "C:\Users\sainluca\OneDrive - Boehringer Ingelheim\UCC CoCo\PCF\PCF-SVG-Control\Samples\PCFSVGControlSampleSolution_0_0_0_1\CanvasApps\pag_technicalmanual_8ff7d_DocumentUri.msapp"


# research
 - https://github.com/WalnutProgramming/room-finder


 - https://github.com/KnotzerIO/indoor-wayfinder
    https://indoor-wayfinder.vercel.app/?position=v35

 - https://github.com/openindoormaps/openindoormaps
    https://openindoormaps.vercel.app/



 - https://jsfiddle.net/jpkf04ov/

 - https://pmc.ncbi.nlm.nih.gov/articles/PMC5659309/

 - https://project-archive.inf.ed.ac.uk/ug4/20223034/ug4_proj.pdf

 - https://gearheart.io/blog/route-finding-for-locationbuilding-svg-maps/















https://github.com/jenschristianschroder/PCF-SVG-Control/blob/master/SVGControl/index.ts
https://github.com/jenschristianschroder/PCF-SVG-Control/blob/master/SVGControl/ControlManifest.Input.xml

https://codepen.io/lucahttp/pen/qBgryWx

https://codesandbox.io/s/3q51zkyl5p?file=/src/SvgContainer.js

https://www.npmjs.com/package/svg-pan-zoom

npm install svg-pan-zoom hammerjs

import svgPanZoom from "svg-pan-zoom"; // import * as svgPanZoom from 'svg-pan-zoom';​
import Hammer from "hammerjs";



https://www.npmjs.com/package/@types/react-svg-pan-zoom
https://www.npmjs.com/package/react-svg-pan-zoom?activeTab=readme
https://www.npmjs.com/package/svg-pan-zoom


https://medium.com/@steveruiz/using-a-javascript-library-without-type-declarations-in-a-typescript-project-3643490015f3
https://pnp.github.io/blog/post/create-first-pcf-component-using-react/


using ts lib on react but not "svg-pan-zoom" but similar proyect
https://codesandbox.io/s/react-svg-pan-zoom-bh90t



from vanilla js to ReactJS
https://codesandbox.io/s/svg-pan-zoom-reactjs-fkrjc5?file=/src/PanZoom.js
https://codesandbox.io/s/svg-pan-zoom-reactjs-with-hammejs-touch-support-fy5377?file=/src/App.js:0-5532

from ReactJS to TypeScript
https://codesandbox.io/s/svg-pan-zoom-reactjs-typescript-5ymmg8?file=/src/App.tsx:0-5718
https://js2ts.com/
https://github.com/jenschristianschroder/PCF-SVG-Control/blob/master/SVGControl/index.ts
