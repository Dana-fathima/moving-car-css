# moving-car-css
moving car
# Car Animation HTML and CSS

This project demonstrates a simple animation of a car moving across the screen using HTML and CSS. The car is composed of multiple sections such as the back, center, front, wheels, windows, and a base stand. The car is animated to move from left to right with a continuous loop, and the wheels are designed to rotate slightly for added realism.

## Features
- **Car Design**: The car consists of three parts: the back, center, and front. Each part has unique styling and color gradients for a smooth visual effect.
- **Animation**: The car moves across the screen with an animation that spans 7 seconds, making it look like the car is constantly driving.
- **Wheel Movement**: The wheels of the car rotate slightly to simulate motion, adding to the effect.
- **Background and Styling**: The background is set to an `antiquewhite` color, providing a pleasant and neutral backdrop for the car's animation. The design also uses linear gradients for color effects on the car body.

## Structure Breakdown
1. **HTML**:
   - The car's components are structured inside a `div` container with a class of `car`.
   - Inside the container, the back, center, and front sections are defined, along with additional components like wheels, windows, and a base stand.
   - The image of the driver is included in the center of the car for a more realistic appearance.

2. **CSS**:
   - The root defines a primary color variable used throughout the car's design.
   - The `@keyframes` animations control the movement of the car and rotation of the wheels.
   - The car's components are styled with gradients and specific positioning to align them correctly.

3. **Animation**:
   - The car moves across the viewport from left to right using the `@keyframes` `speed` animation.
   - The wheels rotate using the `@keyframes` `whe` animation, giving the appearance of the car driving.

## How to Use
1. Clone or download the repository.
2. Open the `index.html` file in a browser to view the animation.
3. The car will animate continuously, moving from left to right, with rotating wheels.

## Example Screenshot
![Car Animation Screenshot](https://i.pinimg.com/1200x/a8/60/09/a860099ac4dd177c77b82a84569ff9c0.jpg)

---

## License
This project is open-source and available for use and modification under the [MIT License](LICENSE).
