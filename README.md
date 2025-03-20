# AirCanvas
Motion-Based Drawing in Air

This project enables motion-based drawing in thin air. Captured colored marker movements via a camera, tracked contours, and drew on a virtual canvas. The system identifies the colored marker and generates a mask. Subsequently, it applies morphological operations—specifically Erosion and Dilation—to the mask. Erosion eliminates impurities, while Dilation restores the original mask after erosion
