**FLATIRON RAILS PROJECT REQUIREMENTS**
Use the Ruby on Rails framework.

Your models must:

1a   • Include at least one has_many, at least one belongs_to, and at least two has_many :through relationships

1b   • Include a many-to-many relationship implemented with has_many :through associations. The join table must include a user-submittable attribute — that is to say, some attribute other than its foreign keys that can be submitted by the app's user

2. Your models must include reasonable validations for the simple attributes. You don't need to add every possible validation or duplicates, such as presence and a minimum length, but the models should defend against invalid data.

3. You must include at least one class level ActiveRecord scope method (Links to an external site.). a. Your scope method must be chainable, meaning that you must use ActiveRecord Query methods (Links to an external site.) within it (such as .where and .order) rather than native ruby methods (such as #find_all or #sort).

4. Your application must provide standard user authentication, including signup, login, logout, and passwords.

5. Your authentication system must also allow login from some other service. Facebook, Twitter, Foursquare, Github, etc...

6. You must include and make use of a nested resource with the appropriate RESTful URLs.

  6a • You must include a nested new route with form that relates to the parent resource

  6b • You must include a nested index or show route

7. Your forms should correctly display validation errors.

  7a. Your fields should be enclosed within a fieldswitherrors class

  7b. Error messages describing the validation failures must be present within the view.

8. Your application must be, within reason, a DRY (Do-Not-Repeat-Yourself) rails app.

    • Logic present in your controllers should be encapsulated as methods in your models.

    • Your views should use helper methods and partials when appropriate.

9. • Follow patterns in the Rails Style Guide (Links to an external site.) and the Ruby Style Guide (Links to an external site.).

10.  Do not use scaffolding to build your project. Your goal here is to learn. Scaffold is a way to get up and running quickly, but learning a lot is not one of the benefits of scaffolding.
