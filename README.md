# OpenCoach 🏸🏋️👟

OpenCoach is an open source application designed to be the simplest fitness accountablilty app ever.

Set fitness goals and plans, all over SMS. No logins. No annoying apps.

Chat with OpenCoach mid-workout and it automatically tracks your progress and saves it to your profile. At the end of each day, you get a clear view of your goals and progressions.


## Features
* Workouts tailored to you. Tell OpenCoach your high-level stats (age, goals, weight, etc.) and get a custom made plan
* Bespoke workout generations every day. Just say your time availablity and your available equipment (including calisthenics)
* It's **free**. Bring your own OpenAI and Twilio keys and it just works. Otherwise, you can subscribe to our hosting solutions for just $5/month. (We have bills to pay, unfortunately).

Most OpenCoach user interactions are over SMS. We don't believe in redesigning iMessage from the ground up. Just shoot it a text.

You can update your workouts, set new goals, and receive progress reports, all through text messages. This makes OpenCoach a portable fitness coach that's always at your fingertips, no matter where you are.

## Running Locally

1. Install dependencies using pnpm:

```sh
pnpm install
```

2. Copy `.env.example` to `.env.local` and update the variables.

```sh
cp .env.example .env.local
```

3. Start the development server:

```sh
pnpm dev
```

## License

Licensed under the [MIT license](https://github.com/shadcn/taxonomy/blob/main/LICENSE.md).

