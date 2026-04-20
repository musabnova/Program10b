# Program 10b - Advanced HTTP Request and Response Handling

## Objective
Develop a servlet program to process user input using HTTP Request and generate dynamic output using HTTP Response.

## Files
- resultServlet.java
- index.jsp
- result.jsp

## Source Code
- Servlet: https://github.com/musabnova/Program10b/blob/master/src/main/java/com/result/resultServlet.java
- Input Page: https://github.com/musabnova/Program10b/blob/master/src/main/webapp/index.jsp
- Output Page: https://github.com/musabnova/Program10b/blob/master/src/main/webapp/result.jsp

## Concept Used
- HttpServletRequest
- HttpServletResponse
- Request parameters
- Data processing in servlet
- RequestDispatcher
- JSP for output

## How it Works
1. User enters input data in index.jsp
2. Form submits data to servlet
3. Servlet processes input (calculation/logic)
4. Processed data is forwarded to result.jsp
5. Output is displayed dynamically

## How to Run
1. Deploy project on Apache Tomcat
2. Open:
   http://localhost:8080/Program10b/
3. Enter data and submit
4. View processed result

## Output

### Input Page
<img src="https://github.com/musabnova/Program10b/blob/master/1.png" width="400"/>

### Result Page
<img src="https://github.com/musabnova/Program10b/blob/master/2.png" width="400"/>

## Result
User input is successfully processed using servlet and displayed dynamically using JSP.
