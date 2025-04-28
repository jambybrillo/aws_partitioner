API Documentation
=================

This section provides documentation for any APIs available within the AWS Cloud Quest system.
If your project exposes RESTful endpoints or integration hooks, document them here.

Example API Endpoints
---------------------

.. code-block:: http

   GET /api/courses
   Response: Returns a list of available courses with details.

.. code-block:: http

   POST /api/enroll
   Body: { "user_id": "<user_id>", "course": "Cloud Practitioner" }
   Response: Enrollment confirmation.

For detailed examples of each endpoint, request parameters, and response schema, refer to the 
API specification documents available within the project repository.
