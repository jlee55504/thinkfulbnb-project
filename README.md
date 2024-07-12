# Thinkfulbnb

Thinkfulbnb is a vacation rental website that allows people to rent out their homes to people who are seeking short-term accommodations in that locale. Thinkfulbnb hosts rent out different kinds of properties, including single rooms, apartments, and unique living spaces such as yachts, houseboats, yurts, tiny houses, and even renovated medieval castles.

## Overview:
This project was made using a mobile-first development approach.

Completed Chegg Skill's "Thinkfulbnb's landing page" "Qualified" project

### Mobile view

![](images/Thinkfulbnb-mobile.png)

### Desktop view

![](images/Thinkfulbnb-desktop.png)

### Existing files

| File         | Description                                                             |
| ------------ | ----------------------------------------------------------------------- |
| `images/`    | A folder containing all the images used for the design.                 |
| `index.html` | The HTML file. |
| `style.css`  | The css file. |

#### Navigation

- The logo stacks on top of the menu links, which are aligned horizontally, as follows:

![Navigation mobile](./images/navigation-mobile.png)

- **Single-page navigation**: Clicking on each navigation link will take the user to the corresponding sections on the page, as follows:

| Link clicked | Take the user to the section with `id` of |
| ------------ | ----------------------------------------- |
| `Stay`       | `id="stay"`                               |
| `About`      | `id="about"`                              |
| `Ideas`      | `id="ideas"`                              |
| `Host`       | `id="host"`                               |

#### HTML form

- In the "Find your perfect vacation rental" section, a form contains the following input fields with the specified types:

  - `Location`: `text` input type, with a placeholder value of "Search destination"
  - `Arrive`: `date` input type
  - `Depart`: `date` input type
  - `Type`: a dropdown list with the following options:
    - Apartment
    - Barn
    - Castle
    - Houseboat
    - Tiny House
    - Yacht
    - Yurt
  - a `"Search"` button

  - the labels (i.e., "Location", "Arrive", "Depart", "Type") and their corresponding form fields are aligned towards the opposite ends of each row

The final form design looks as follows:

![Search form mobile](./images/search-form-mobile.png)

#### Vertical content alignment

- The content in the remainder of the sections (i.e., "About", "Ideas", "Want to become a Thinkfulbnb Host?"), including any text and images, stack on top of each other.

#### Responsive images

- All the images match whatever container width they are placed within, and changing the container sizes will update the image sizes appropriately.

#### Media query: Desktop view

- In `style.css`, a media query has been created for screens that are wider than `768px`.

Within the media query, CSS has been written to create the following designs for desktop:

- The logo and the navigation menu links are spaced apart from each other, like this:

![Navigation desktop](./images/navigation-desktop.png)

- The search form input fields and the button are horizontally aligned, like this:

![Search form desktop](./images/search-form-desktop.png)

- The items in the "About" section are horizontally aligned. The paragraph content is vertically centered and about twice as wide as each image item, like this:

![About desktop](./images/about-desktop.png)

- The "Ideas" images are displayed in a 2 by 2 grid (see the desktop design shared above).

- The items in the "Want to Become a Thinkful Host?" section are horizontally aligned. The paragraph content is vertically centered and as wide as each image item, like this:

![Host desktop](./images/host-desktop.png)
