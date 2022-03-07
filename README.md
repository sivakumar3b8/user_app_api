Rspec Test Cases

Model--User

  validation test
    ensure first_name presence
    ensure last_name presence
    ensure email presence
    should save successfully

    Routing User
      has route to Index action
      has route to Show action
      has route to Create action
      has route to Update action
      has route to Destroy action


Users
  GET /users
    index action has status  code 200
  GET /users/1
    show action has status  code 200
  POST /users
    create action has status  code 200
  PATCH/PUT /users/1
    update action has status  code 200
  /users/1
    Destroy action has status  code 200

