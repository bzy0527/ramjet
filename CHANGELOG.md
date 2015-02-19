# changelog

## 0.3.0

* If possible, and `options.useTimer` is not used, mogrify will use precomputed CSS keyframes to move the work off the main thread. This results in a vastly smoother experience on mobile (and desktop in some cases), at the cost of a slight loss in visual fidelity (which is barely noticeable for animations less than ~500ms)

## 0.2.0

* Rewrote as ES6 modules
* Started maintaining a changelog