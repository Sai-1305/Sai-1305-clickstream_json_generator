# Sample clickstream data generator

---

## Want to generate clickstream data for practice purpose?
---

This project is all about generating some data that can be used for practising on "clickstream" data related problem statements. This is strictly an assumption about the log of events. In reality, there can be a lot more properties or details about the user clickstream event logs. I looked for samples from [JSON Generator](https://www.jsongenerator.io/schema), [JSON GENERATOR](https://json-generator.com/), [Mockaroo](https://www.mockaroo.com/), etc. The data provided by those apps was good, but just my use case was different. As per my use case, I considered an application similar to dating apps. I wanted to derive some metrics and then perform analysis on the application's event logs. Hence, I tried to mimic the architecture but in a very high-level and simple format.

---

> The steps that I used are:
> > 1. Draft a schema.
> > 2. Improvise the schema with more specifics as per the use case. (Take help from other apps like [JSON Schema Validator](https://www.jsonschemavalidator.net/), [JSON Schema](https://json-schema.org/learn)).
> > 3. Use Javascript, [stack overflow](https://stackoverflow.com/) and [Perplexity](https://www.perplexity.ai/) to write and modify the code.

---

> Usage:
> > 1. Change the **numberOfRecords** on *line: 7* of *[generate_data.js](./src/generate_data.js)* to get desired number of records.
> > 2. Install [Node.js](https://nodejs.org/en/download/prebuilt-installer).
> > 3. Install the dependencies.
> > > > Navigate to the [root directory](./) (In this directory, you can see the directories [src](./src/), [schemas](./schemas/), [output](./output/) and the file [README.md](./README.md)). Run the command:<br>
> > > > `npm install`
> > > > `npm install json-schema-faker moment`
> > 4. To run the application, run the command:<br>
> > > > `node src/generate_data.js`
> > 5. Access the output json file in [output directory](./output/)

---

*Feel free to change the schema or any other particulars as per your requirement*