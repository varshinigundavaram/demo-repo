# Test PBI
import { Report } from 'powerbi-report-component';
<Report 
     tokenType="Embed" // or "Aad"
     accessToken="Test" // accessToken goes here
     embedUrl="https://app.powerbi.com/reportEmbed?reportId=<741575e2-9b5f-4686-96cd-4104a12e4250>&groupId=<me>" // embedUrl goes here
     embedId="741575e2-9b5f-4686-96cd-4104a12e4250" // Report or Dashboard ID goes here
     permissions="All" // or "View"
     style={myStyleObject}
/>
