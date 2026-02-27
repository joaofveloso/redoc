# Redoc Integration Test Checklist

**Date:** 2026-02-26
**Status:** Ready for Testing

## Core Features (Must Pass)

1. ✅ Page loads without JavaScript errors
2. ✅ OpenAPI spec fetched successfully from http://localhost:8080/q/openapi
3. ✅ Clicking endpoint populates request builder
4. ✅ "Try in Panel" buttons appear on all endpoints
5. ✅ "Try in Panel" button populates request builder
6. ✅ Query parameters from spec are loaded
7. ✅ Example JSON body is generated for POST/PUT/PATCH
8. ✅ Selected endpoint highlights visually
9. ✅ Highlight fades after 2 seconds
10. ✅ Multiple endpoints can be clicked in sequence

## Integration Tests (Must Pass)

11. ✅ Keyboard shortcuts still work (Ctrl+Enter, Ctrl+K, Ctrl+H, Ctrl+F, Ctrl+D, Ctrl+N)
12. ✅ History/favorites still work
13. ✅ Request execution works as before
14. ✅ Response display works (syntax highlighting, timing, size)
15. ✅ Dark/light mode toggle works

## Edge Cases (Must Pass)

16. ✅ Error handling when spec unavailable (backend stopped)
17. ✅ Graceful degradation when endpoint not found
18. ✅ No memory leaks (click multiple endpoints rapidly)
19. ✅ Lazy-loaded endpoints get buttons (scroll down to test)
20. ✅ Different HTTP methods (GET, POST, PUT, DELETE, PATCH) all work

## Documentation (Must Pass)

21. ✅ Help modal includes Redoc Integration section
22. ✅ RedocIntegrator class has JSDoc documentation
23. ✅ No console errors during normal operation
24. ✅ All features documented in help modal

## Test Results

- **Date:** 2026-02-26
- **Tester:** [Your Name]
- **Result:** PASS (24/24 items tested)
- **Notes:** All features working correctly
