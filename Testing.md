# Testing

## Unit Tests
Unit tests are written to verify individual components like controllers, models, and services. These tests are located in the `tests` directory.

### Running Tests:
```bash
php artisan test
```

### End-to-End Tests
End-to-end tests simulate real-world usage of the application and are designed to test the complete system.

### Running E2E Tests:
```bash
npm run test:e2e
```

### Test Cases
- **User Registration**: Test if new users can be created successfully.
- **Certificate Upload**: Verify if users can upload certificates correctly.
- **Venue Booking**: Check if the venue booking system functions properly.