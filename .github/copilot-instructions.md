# Enhanced AI Assistant Standards

## Core Documentation Reference Hierarchy

1. **Primary Project Documents**
    - Project Overview
    - Implementation Phases
    - Implementation Quality Gates
2. **Technical Standards**
    - Performance Standards and Monitoring
    - Accessibility Standards
    - Version Control Standards
    - Theme Documentation System
    - Security Standards
3. **Shopify Guidelines**
    - Dawn Theme Architecture
    - Performance Best Practices
    - Design Guidelines
    - Accessibility Requirements

## Development Approach

### Research Phase

1. Review relevant documentation sections
2. Identify applicable standards and requirements
3. Assess potential impacts on:
    - Performance
    - Accessibility
    - Theme compatibility
    - Mobile responsiveness

### Implementation Phase

1. Follow Dawn theme structure
2. Use documentation markers consistently
3. Implement mobile-first approach
4. Test against quality gates
5. Document all customizations

### Documentation Standards

### Custom Code Markers

```
{% comment %}
@fui-doc [component-name]
deps=["list", "of", "dependencies"]
customizations="Description of changes made"
impact: "Performance/accessibility considerations"
{% endcomment %}

```

### Theme Modifications

```
{% comment %}
Custom FUI: [brief description]
- Modification details
- Reason for change
- Related components affected
{% endcomment %}

```

### Version Control Standards

1. **Commit Message Format**

```
Custom FUI: [action] [component]
- [Detailed description]
- [Impact on functionality]
- [Documentation updates]

```

1. **Branch Naming**

```
feature/fui-[component-name]
fix/fui-[component-name]
docs/fui-[component-name]

```

## Implementation Guidelines

### Apple-Inspired Interface Elements

- Implement subtle animations
- Focus on typography and whitespace
- Maintain minimalist design principles
- Ensure smooth transitions

### Dawn Theme Integration

- Preserve core theme functionality
- Document all customizations
- Maintain update compatibility
- Test theme changes thoroughly

### Performance Requirements

- Follow mobile-first development
- Optimize asset loading
- Monitor Core Web Vitals
- Test across devices and browsers

## Communication Standards

### Response Format

1. Acknowledge the request
2. Reference relevant documentation
3. Provide step-by-step guidance
4. Include code examples
5. Note potential impacts
6. Document changes properly

### Code Modification Process

1. Identify target location
2. Show existing code
3. Provide replacement code
4. Include documentation markers
5. Note any dependencies
6. Test recommendations

## Quality Assurance

### Pre-Implementation Checklist

- [ ]  Review relevant documentation
- [ ]  Check performance impact
- [ ]  Verify accessibility compliance
- [ ]  Test mobile responsiveness
- [ ]  Document changes
- [ ]  Validate Dawn compatibility

### Testing Requirements

- Cross-browser compatibility
- Mobile device testing
- Performance benchmarks
- Accessibility standards
- Theme update compatibility

## Documentation Updates

When providing guidance, reference documentation using:
"For [topic], see [Document].md > [Section]"

Example:
"For performance standards, see Performance Standards and [Monitoring.md](http://monitoring.md/) > Core Web Vitals Targets"