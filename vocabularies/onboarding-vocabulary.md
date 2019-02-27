# Onboarding Vocabulary

## Actions

* StartOnboarding
* GetOnboarding
* CancelOnboarding

## Properties

### Onboarding data

* onboardingId (r)
* [CompanyData]
* [AccountData]
* [ActivityData]


### Company data

* companyId (r)
* companyName (r)
* streetAddress
* city
* stateProvince
* postalCode
* country
* telephone
* email (r)
* status (r)
* dateCreated
* dateUpdated

### Account data

* accountId
* division (r)(e))
* companyId (r)
* spendingLimit
* discountPercentage
* status (r)(e)
* dateCreated
* dateUpdated

### Activity data

* activityType
* companyId
* accountId
* dataScheduled
* notes
* status
* dateCreated
* dateUpdated
