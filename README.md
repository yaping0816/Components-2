# Components II

## Running this project

This project is set up with [Parcel Bundler](https://parceljs.org/), an npm package
that compiles our frontend assets and comes with an integrated development server.

The dev server runs on `http://localhost:1234` by default, but will use another port
number if `1234` is being used by another application.

- Clone the repo.
- Navigate into the project folder.
- Run `npm install` to download the project's dependencies.
- Run `npm start` to compile the project and spin up a dev server on `localhost`.

<!-- what is synchronous code -->
- executing code one line after another
- next code only run after the first code complete, waiting and then proceed, this is how programing language usually work, but not JS
- it can be blocking and it leads to long wait times where you have to sit there and let you broswer think for a while before executing before moving on
- Blocking can happens especially when we start using large sets of data, or interating with APIs that have load or wait times and doing any thing like API request...
- blocking means the compiler just sit here and waiting, the website will appaer frozon
- other programming language would use multi-threading to deal with the fact that this thread is basically blocked there waitng fot the network respond to the arrive

<!-- what is asynchronous code -->
- allow us to run code seperately and independently
- it's slightly different than parellel execution like if you were to set up a bunch of jobs and start them at the same times and see they execute on their own, that's not what happening in JS
- JS asynchronous code is still being like queued or being put in the line however it starts i

<!-- what is axios -->
- axios is a js library that do the network request.

<!-- what is an endpoint -->
- endpoints is a pattern, an URL like in 'axios.get(URL)', an address on the internet. It's the means through which we interact with data services. So the data services potenially services all kinds of resources over the network. So the 
endpoint containes several pieces. First one is the http or https, second one is human readable address of a particular machine(lambdaschool.com), particular resource address on the server(....com/friends)

<!-- what is HTTP -->
- networking protocal

<!-- what is Promise and why do we need it -->
- A promise is an object that represents the result of a computation
- Why do we need the Promise? B/C some compiutations take forever in computer time and we need sometihng to represent it at the same time so there is no blocking. It has the capbility to take a callback where you say ecactly what to do with the data when it arrived.

<!-- use client, like HTTPie -->
- don't write axios code without investagating your endpoint, how it fails or how it pass