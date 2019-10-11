# Bootcamp 9 complete aplication meetapp

## Authentication ♥️ :hearts:

- :heavy_check_mark: To make the user auth, JWT was the choise.
- :heavy_check_mark: To login the user must use :email: e-mail and :key: password.
- :heavy_check_mark: The fields of login and sing in are validated by Yup.

## :memo: User register and update

- :heavy_check_mark: The user can register using name, e-mail and password.
- :heavy_check_mark: To update the password user need to send a password confirmation and the old password.
- :heavy_check_mark: User passwords are all encripted.
- :heavy_check_mark: All register and update field requests are checked via Yup.

## :calendar: MeetUp subscription

- :heavy_check_mark: The user can subscribe to meetups that are not of him.
- :heavy_check_mark: The user can't subscribe to meetups that already happened.
- :heavy_check_mark: The user can't subscribe to the same meetup two times.
- :heavy_check_mark: The user can't subscribe to meetups that happen at the same time.
- :heavy_check_mark: The owner of the meetup receive a email when a user subscribe to one of his meetups.

## :bookmark_tabs: MeetUps list

- :heavy_check_mark: MeetUps can be list by date and are paged by 10 meetups.

## :round_pushpin: Subscription list

- :heavy_check_mark: There is a route to list all future meetups that the current user is subscribed.

# :star: Extra

- Added a splash screen to the mobile app.
- Added a icon to the mobile app.
- Added differente messages to each error, these messages are coming from the backend and showed on forntend by toasts.
- Added styled toasts to the mobile app instead of the default Alert of react-native.
- Added tests to the session controller and the user controller.
- Web responsive layout.

# :exclamation: Possible improvements

- Add field validation to the mobile application.
- Add some animations to the mobile and web application.
- Create tests for ALL the controllers and components.
- Add cache to routes like the meetup list route.
- Support to iOS.

# :wrench: Running the project

- Yout need to set up all the react-native enviroment.
- Install docker and create a postgres and redis container.
- Clone this repository.
- Install all dependencies using the command `yarn` in each directory, backend, mobile and frontend.
- Enter backend directory and fill the `.env` file.
- Enter backend directory and run `yarn run-dev`.
- Enter frontend directory and run `yarn start`.
- Enter mobile directory and run `react-native run-android` while you are running a Android emulator.

## :pencil2: Observation:

- I wasn't able to test the application on iOS because I don't have a MacBook to do it.

# :fire: Used technologies

- ReactJS
- React Native
- NodeJS
- Node Mailer
- Styled Components
- Reactotron
- Redux
- Redux Saga
- Postgres
- Docker
- Redis
- Other React and Node libs.

# :man: Contributors

- @phellipe
