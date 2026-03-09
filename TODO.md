# TODO - Reduce Project Image Sizes

## Task
Reduce image size and placeholder size for Project 1 and Project 3 in the projects section.

## Plan
- [x] Add CSS rules to reduce image/placeholder size for Project 1
- [x] Add CSS rules to reduce image/placeholder size for Project 3

## Changes made in style.css:
1. Added specific rules for Project 1 (`.projects .project-card:nth-child(1)`)
2. Added specific rules for Project 3 (`.projects .project-card:nth-child(3)`)
3. Matched Project 2's reduced size (30% padding, 240px max-height)

## Result
All three projects now have consistent, reduced image sizes:
- padding-top: 30%
- max-height: 240px
- object-fit: cover
