### Specs

Describe: addEmail()
Test: "Store the contacts email address on an instance of a contact"
Code: const newContact = new Contact("Bobby", "Richards", 123);
Code: newContact.addEmail("bobby456@yo.com");
Expect(newContact.addEmail("bobby456@yo.com")).toEqual("bobby456@yo.com");

Describe: addAddress()
Test: "Store the contacts address on an instance of a contact"
Code: const newContact = new Contact("Bobby", "Richards", 123, "bobby456@yo.com");
Code: newContact.addAddress(123 NE 1st St. Portland, OR 97213);
Expect(newContact.addAddress("123 NE 1st St. Portland, OR 97213)).toEqual("123 NE 1st St. Portland, OR 97213);