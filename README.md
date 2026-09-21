# sumofnumbers

ICS 314 practice quiz: four TypeScript functions that add the numbers in a list.

## Run

1. Run `npm install`.
2. Run `npx tsc` to compile `sumofnumbers.ts` into `sumofnumbers.js`.
3. Open `index.html` in a browser and open its developer console.
4. Each of the four examples prints `10`.
5. Run `npm run lint` to check the course coding standards.

## Four approaches

- `sumFor`: visits each array index with a for-loop and adds its value to a running total.
- `sumWhile`: does the same with a while-loop and manually advances the index.
- `sumRecursion`: returns zero for an empty list; otherwise adds the first value to the sum of the remaining list.
- `sumTheFunctionalWay`: uses `reduce` to accumulate a total, starting at zero.

See [Estimation Log](ESTIMATION_LOG.md) for the reported attempt time, reflection, and AI assistance disclosure.
