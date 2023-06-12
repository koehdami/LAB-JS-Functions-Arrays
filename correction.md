great job!
just for you to know, when we have only one line of code inside an if statement we can do without curly braces, having less lines of code and usually better readability, for example:

  if(words.length < 1) return null;
  else if(words.length === 1) return words[0];
