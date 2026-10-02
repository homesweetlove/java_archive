[![English](https://img.shields.io/badge/README-English-24292f?style=for-the-badge)](./README.md) [![한국어](https://img.shields.io/badge/README-%ED%95%9C%EA%B5%AD%EC%96%B4-24292f?style=for-the-badge)](./README.ko.md)

# Random Timetable Recommender

> Final project for the Java Programming course.

This desktop application collects available courses and randomly generates timetables that match the user's conditions. Instead of manually assembling a schedule from scratch, users can choose from generated options when registering for classes.

If registration for a selected course fails, the application can also recommend alternative courses.

## Design

The project is designed and implemented as a desktop GUI application.

Project name: **Timetable Recommendation System**

---

### Detailed Features

#### When a timetable is selected
- Display the timetable in a JTable
- Show the corresponding course list

#### When a course is selected
- Display detailed course information

#### When course registration fails
- Recommend alternative courses based on:
  - Same department
  - Same course category
  - Similar courses
