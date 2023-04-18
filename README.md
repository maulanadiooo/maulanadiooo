class Profile {
  String name;
  String age;
  String occupation;
  String location;
  Map<dynamic, String> contacts;

  Profile({
    required this.name,
    required this.age,
    required this.occupation,
    required this.location,
    required this.contacts,
  });

  static Profile init() {
    Profile myProfile = Profile(
      name: 'Dio Maulana',
      age: 'Unknown',
      occupation: 'Mobile Developer',
      location: 'Localhost, Indonesia',
      contacts: {
        "email": "diomaulana@jasadigital.co.id",
        "telegram": "maulanadioo"
      },
    );
    return myProfile;
  }
}

void main() {
  Profile.init();
}
