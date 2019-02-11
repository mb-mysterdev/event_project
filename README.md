
rails db:create <br> <br>
rails db:migrate <br> <br>
rails db:seed <br> <br>
rspec <br> <br>
rails console <br> <br>
u = User.create(first_name: "John", last_name: "Doe", email: "votremail@MAILVALIDE.COM", description: "La super desc de l'utilisateur que tu viens de créer", encrypted_password: "azerty") <br> <br>
e = Event.create(title:'May awesome event', description:'That will be really be an awesome event !', start_date: Time.now+30, duration: 90, location: 'Ibiza', price: 100, admin: u) <br> <br>
a = Attendance.create(event: id, user: id, stripe_customer_id: "25418545") <br> <br>

MOMO POLO YANNICK
