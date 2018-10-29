# From Dagger to Koin, a step by step migration guide

This project shows how to migrate the thermosiphon Dagger's sample to Koin, step by step.

## The article

This project has been explained in detail from the article: [From Dagger to Koin, a step by step migration guide](https://medium.com/@giuliani.arnaud/the-thermosiphon-app-from-dagger-to-koin-step-by-step-a09af7f5b5b1)

## Gradle 

To build the project (Dagger generation), just hit the following command:

```gradle
./gradlew clean build
```

## Migration step by step

Below the git *tags* of the project, to follow the migration steps:

* DAGGER - init commit with app managed by Dagger
* STEP1 - `Heater` component migrated
* STEP2 - `Pump` component migrated
* STEP3 - `CoffeeMaker` component migrated
* KOIN - shut off Koin logs
