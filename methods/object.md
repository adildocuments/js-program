https://chatgpt.com/share/67b81fab-c160-8009-bfe5-609fd2bac26c

In JavaScript, objects come with various built-in methods that allow you to manipulate and interact with their properties. Below is a categorized list of key object methods:

1. Object Creation & Manipulation
   Object.create(proto, [propertiesObject]) → Creates a new object with the specified prototype.
   Object.assign(target, ...sources) → Copies properties from source objects to a target object.
   Object.defineProperty(obj, prop, descriptor) → Defines a new property with specific characteristics.
   Object.defineProperties(obj, props) → Defines multiple properties at once.
   Object.freeze(obj) → Prevents any modifications to an object.
   Object.seal(obj) → Prevents adding/removing properties but allows modifying existing ones.
   Object.preventExtensions(obj) → Prevents adding new properties to an object.
2. Object Inspection & Property Handling
   Object.keys(obj) → Returns an array of property names (keys).
   Object.values(obj) → Returns an array of property values.
   Object.entries(obj) → Returns an array of key-value pairs.
   Object.getOwnPropertyNames(obj) → Returns an array of all properties (including non-enumerable ones).
   Object.getOwnPropertySymbols(obj) → Returns an array of symbol properties.
   Object.getOwnPropertyDescriptor(obj, prop) → Returns property descriptor for a specific property.
   Object.getOwnPropertyDescriptors(obj) → Returns descriptors for all properties.
   Object.hasOwn(obj, prop) → Checks if an object has a property (ES2022).
   Object.hasOwnProperty(prop) → Checks if a property exists on an object (older method).
   Object.is(obj1, obj2) → Checks if two values are the same (better than ===).
   Object.isFrozen(obj) → Checks if an object is frozen.
   Object.isSealed(obj) → Checks if an object is sealed.
   Object.isExtensible(obj) → Checks if new properties can be added.
3. Object Prototypes & Inheritance
   Object.getPrototypeOf(obj) → Returns the prototype of an object.
   Object.setPrototypeOf(obj, prototype) → Sets the prototype of an object.
4. Object Conversion & Iteration
   Object.toString() → Converts an object to a string.
   Object.toLocaleString() → Converts an object to a localized string.
   Object.valueOf() → Returns the primitive value of an object.
   Object.fromEntries(array) → Converts an array of key-value pairs into an object.
   These methods help you manage and manipulate objects effectively in JavaScript. Let me know if you need detailed explanations or examples for any of them! 🚀
