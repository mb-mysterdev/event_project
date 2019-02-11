
rails db:create
rails db:migrate
rails db:seed
rspec
rails console
u = User.create(first_name: "John", last_name: "Doe", email: "TONEMAILVALIDE@MAILVALIDE.COM", description: "La super desc de l'utilisateur que tu viens de créer", encrypted_password: "azerty")
e = Event.create(title:'May awesome event', description:'That will be really be an awesome event !', start_date: Time.now+30, duration: 90, location: 'Ibiza', price: 100, admin: u)
a = Attendance.create(event: id, user: id, stripe_customer_id: "25418545")
