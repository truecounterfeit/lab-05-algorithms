# CSS Layouts

**User Story**
As a developer, I need to understand the various techniques of laying content out so that I can easily adapt to designs & mocks.

Given this markup:

    <div>
        <ul>
    	    <li>One</l1>
            <li>Two</li>
            <li>Three</li>
        </ul>
    </div>

**Case #1 - Describe the visual when this CSS is applied**

      div {
        border: 1px solid #000;
      }

      ul {
        list-style-type:none;
        margin:0;
        padding:0;
      }

      li {
    	border: 1px solid red;
    	float: left;
    	height:25px;
    	width:100px;
    	text-align:center;
      }

**Progressive Requirements**

 1. Display the grid and container with a quality border, padding, margins, colors
 2. Move the item "Two" to the far right of the screen
 2. For Item 1: Top Align the text
 3. For Item 2: Middle Align the text
 4. For Item 3: Bottom Align the text
 5. Move Item 3 to the far left of the screen
 6. Put them all back in order, from left to right
 6. When you click any of the items, move that item to the first position

**Bonuses (5 Points Each)**

 - Achieve this with 5 different layout models (can you name 5 different layout models?)
 - Achieve this with only vanilla JS
 - Achieve this without JS