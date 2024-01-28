# Debugging

## 1. Understand the System

- Read the manual

## 2. Make it Fail

- You have to make it fail as regularly as possible
- Stimulate the failure (Don't wait for the next big storm)
- Record everything and find the signature of intermittent bugs

## 3. Quit Thinking and Look

- Looking means putting in breakpoints, adding debug statements, monitoring program values...

## 4. Divide and Conquer

- Narrow the search
  - Upstream: good, clear water
  - Downstream: bad, smelly pink water
- Fix the bugs you know about

## 5. Change One Thing at a Time

- Isolate the key factor
- Compare with a good one
- What did you change since the last time it worked?
  - Sometimes the problem has existed but doesn't show up until something else changes

## 6. Keep an Audit Trail