### Specs

Describe: addEmail()
Test: "Store the contacts email address on an instance of a contact"
Code: const newContact = new Contact("Bobby", "Richards", 123);
Code: newContact.addEmail("bobby456@yo.com");
Expect(newContact.addEmail("bobby456@yo.com")).toEqual("bobby456@yo.com");

