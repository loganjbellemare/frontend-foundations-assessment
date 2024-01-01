# Thinkfulbnb

Thinkfulbnb is a vacation rental website that allows people to rent out their homes to people who are seeking short-term accommodations in that locale. Thinkfulbnb hosts rent out different kinds of properties, including single rooms, apartments, and unique living spaces such as yachts, houseboats, yurts, tiny houses, and even renovated medieval castles.

For this assignment, I implemented Thinkfulbnb's landing page in HTML & CSS

A deployed version of this site can be viewed [here](https://loganjbellemare.github.io/frontend-foundations-assessment/)!

## Thinkfulbnb views

This layout is responsive on both mobile and desktop views!

### Mobile view

![](images/Thinkfulbnb-mobile.png)

### Desktop view

![](images/Thinkfulbnb-desktop.png)

### Existing files

| File         | Description                                                             |
| ------------ | ----------------------------------------------------------------------- |
| `images/`    | A folder containing all the images used for the design.                 |
| `index.html` | The HTML for the page. |
| `style.css`  | The CSS file for styling.  |

### Tasks

For this assignment, I followed a mobile-first development approach. To pass this assignment, you must complete the tasks detailed below.

Used flexbox, and **not** floats, to achieve the desired layouts.

**NOT** expected to match the designs pixel by pixel, as long as the required layout is satisfied.

#### Navigation

- Menu links are aligned horizontally, as follows:

![Navigation mobile](./images/navigation-mobile.png)

- Single page navigation. Clicking on each link will take the user to the corresponding sections on the page, as follows:

| Link clicked | Take the user to the section with `id` of |
| ------------ | ----------------------------------------- |
| `Stay`       | `id="stay"`                               |
| `About`      | `id="about"`                              |
| `Ideas`      | `id="ideas"`                              |
| `Host`       | `id="host"`                               |

#### HTML form

- In the "Find your perfect vacation rental" section, form contains the following input fields with the specified types:

  - `Location`: `text`
  - `Arrive`: `date`
  - `Depart`: `date`
  - `Type`: a dropdown list with the following options:
    - Apartment
    - Barn
    - Castle
    - Houseboat
    - Tiny House
    - Yacht
    - Yurt
  - a `"Search"` button

Final form design should look as follows:

![Search form mobile](./images/search-form-mobile.png)

#### Vertical content alignment

- The content in the remainder of the sections (i.e., "About", "Ideas", "Want to become a Thinkfulbnb Host?"), including any text and images, is stacked on top of each other. Refer to the mobile design shared above.

#### Responsive images

- Images match whatever container width they are placed within, and changing the container sizes will update the image sizes appropriately.

#### Media query: Desktop view

- Media query breakpoint is set to `768px`.

Upon breakpoint, site expands to look like this:

- The logo and the navigation menu links are spaced apart from each other, like this:

![Navigation desktop](./images/navigation-desktop.png)

- The search form input fields and the button are horizontally aligned, like this:

![Search form desktop](./images/search-form-desktop.png)

- The items in the "About" section are horizontally aligned. The paragraph content is vertically centered and always is about twice as wide as each image item, like this:

![About desktop](./images/about-desktop.png)

- The "Ideas" images are displayed in a 2 by 2 grid (see the desktop design shared above).

- The items in the "Want to Become a Thinkful Host?" section are horizontally aligned. The paragraph content is vertically centered and as wide as each image item, like this:

![Host desktop](./images/host-desktop.png)
#frontend-foundations-assessment
