# Frontend Challenege

## Time estimages for all components

- Header - 2 hours (3 with mobile nav, although both probably faster using a UI template - TailwindUI have a free nav with dropdown menu which is responsive)
- Hero - 1.25 hour
- Image and Text block - 30 mins
- Exceptional accounting - 2 hours
- 2 column text block - 30 mins
- peace of mind - 45 mins
- quote - 20 mins
- blog - 1 hour
- form cta - 30 mins
- team cta - 20 mins
- footer 45 mins

These timings are based on how complex each component feels upfront. There might be hidden issues while developing so I've added in some leeway.

## Blog listing

Time estimate - 1 hour

- no hover state in design
- blog posts aren't exactly center but look like they should be so I've made them centered (143px right and 152px left)
- hard to tell pixels under 'blog' heading as text box is too big, best guess.
- is 12px accessible?
- I'd usually create a blogCard component and then loop over in blogListing but as this is static I've just put all 3 cards in blogListing.
- linear gradient was rotated 90 degrees so copying the code from the properties was wrong. Also not full height so had to guess %.

Time taken: 1 hour 13 minutes

## Footer

Time estimate - 45 minutes

Time taken - 38 mins

- tried installing Oh Vue Icons but the icons weren't the same. 

## Installation Steps

- Clone the project
- Navigate to the project directory cd frontend-challenge
- Install dependencies with `npm install`
- `npm run dev`