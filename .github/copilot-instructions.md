# Copilot Instructions for Chip In

## About This Repository

This is a Firebase React Native based repository called ChipInMobile being built with help from Copilot, Gemini, ChatGPT, and other AI assistants. It is primarily responsible for building the app called **Chip In** - an event management organizer, group funding, and communication tool.

## Code Standards

### General Guidelines
- Follow React Native and JavaScript/TypeScript best practices
- Maintain existing code structure and organization
- Write clean, readable, and maintainable code
- Use consistent naming conventions throughout the codebase
- Document complex logic and public APIs

### Required Before Each Commit
- Ensure all code is properly formatted
- Test your changes locally before committing
- Verify that no unintended files are included in commits

### Development Flow
- Test functionality thoroughly in both iOS and Android when applicable
- Verify Firebase integration and data flows
- Check that UI changes work across different screen sizes
- Ensure authentication and authorization work correctly

## Repository Structure

As this repository grows, organize code following React Native best practices:
- `src/`: Source code for the application
  - `components/`: Reusable React components
  - `screens/`: Screen components for navigation
  - `services/`: Firebase and other service integrations
  - `utils/`: Utility functions and helpers
  - `context/`: React Context providers
  - `navigation/`: Navigation configuration
- `assets/`: Images, fonts, and other static resources
- `config/`: Configuration files
- `docs/`: Documentation

## Key Guidelines

1. **Onboarding**: Focus on understanding the existing codebase before making changes
2. **Conflict Resolution**: 
   - Look ahead to resolve conflicts before they become unmergeable
   - The most recent change to a file is very likely the edit to keep
   - When in doubt, prefer incoming code conflicts over older code
3. **Code Quality**:
   - Follow React Native and JavaScript/TypeScript idioms
   - Use functional components and hooks
   - Implement proper error handling
   - Write unit tests for new functionality when appropriate
4. **Firebase Integration**:
   - Follow Firebase best practices for authentication, database, and storage
   - Implement proper security rules
   - Handle offline scenarios gracefully
5. **User Experience**:
   - Design with user-friendliness in mind
   - Keep the user interface simple and intuitive
   - Make complex functions easily accessible to users
   - Ensure responsive design across different device sizes
6. **Decision Making**:
   - Use understanding of the app and complex variation of outcomes to apply the best decision
   - Maintain the app's core structure and intention
   - Consider edge cases and handle them appropriately

## Contributing

When contributing to this repository:
- Make minimal, focused changes
- Test thoroughly before committing
- Follow the existing code style and patterns
- Update documentation when adding new features
- Consider the impact on both iOS and Android platforms

## AI Assistant Guidelines

When working with this codebase:
- Understand the context before making changes
- Preserve working code unless there's a clear reason to modify it
- Follow the conflict resolution strategy (prefer recent changes)
- Maintain focus on user experience and simplicity
- Consider the full stack (React Native, Firebase, mobile platforms)
