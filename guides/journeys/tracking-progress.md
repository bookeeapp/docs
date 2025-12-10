---
title: 'Tracking Journey Progress'
description: 'Monitor member advancement, analyze journey effectiveness, and optimize the member experience'
---

# Tracking Journey Progress

Effectively monitoring member progress through your journeys is essential for maximizing engagement and optimizing the experience. Kenko provides robust tracking tools to help you understand how members are advancing and where they might need additional support.

## Journey Analytics Dashboard

<Frame>
  ![Journey Analytics Dashboard](/images/journey-analytics-dashboard.png)
</Frame>

The Journey Analytics Dashboard is your central hub for monitoring all journey-related metrics. Access it by navigating to **Marketing > Journeys > Analytics**.

### Key Performance Indicators

<Grid>
  <div>
    <Metric 
      title="Enrollment Rate" 
      tooltip="Percentage of eligible members who join the journey" 
    />
    Track how many members are joining your journeys relative to those who have access. Low enrollment may indicate promotion issues or lack of perceived value.
  </div>
  <div>
    <Metric 
      title="Completion Rate" 
      tooltip="Percentage of enrolled members who finish the entire journey" 
    />
    The ultimate measure of journey success. Industry benchmarks suggest aiming for at least 30-40% completion rates for longer journeys.
  </div>
  <div>
    <Metric 
      title="Stage Conversion" 
      tooltip="Percentage of members who advance from one stage to the next" 
    />
    Identifies "drop-off points" where members tend to disengage, helping you target improvements to specific stages.
  </div>
  <div>
    <Metric 
      title="Time to Completion" 
      tooltip="Average time taken to complete the journey" 
    />
    Helps you understand if members are progressing at the expected pace or if adjustments are needed to duration estimates.
  </div>
</Grid>

## Monitoring Individual Member Progress

To track specific members' journey advancement:

1. Go to **Members > Member List**
2. Use the **Journey Status** filter to find members in a specific journey
3. Click on a member to view their **Journey Progress** tab
4. Here you'll see:
   - Current stage and progress percentage
   - Time spent in each completed stage
   - Upcoming requirements to advance
   - Any blockers or issues preventing progression

<Tip>
You can export member progress reports by clicking the **Export Data** button in the top-right corner of the Journey Progress screen.
</Tip>

## Identifying At-Risk Members

Kenko automatically flags members who may be at risk of abandoning their journey based on:

- Inactivity periods exceeding stage expectations
- Missed milestone deadlines
- Low engagement with journey communications
- Negative feedback on journey elements

To view and manage at-risk members:

1. Go to **Marketing > Journeys > [Journey Name] > At-Risk Members**
2. Review the list of flagged members and their specific risk factors
3. Use the provided intervention tools (described below)

## Intervention Strategies

<AccordionGroup>
  <Accordion title="Automated Interventions">
    Configure system-triggered support for stalled members:
    
    1. Navigate to **Journey Settings > Interventions**
    2. Set up automated actions based on triggers:
       - Send encouragement emails after X days of inactivity
       - Offer alternative paths if a member is stuck
       - Provide additional resources for challenging stages
       - Automatically extend deadlines if progress is slow
  </Accordion>
  
  <Accordion title="Manual Outreach">
    For personalized intervention:
    
    1. Select members from the At-Risk list
    2. Choose **Start Outreach**
    3. Select from outreach templates or create a custom message
    4. Schedule a follow-up task for your team
    5. Document the intervention in the member's journey notes
  </Accordion>
  
  <Accordion title="Journey Modifications">
    Sometimes the journey itself needs adjustment:
    
    1. Analyze drop-off points in the **Stage Conversion** report
    2. Use the **Edit Journey** option to modify problematic stages
    3. Consider adding:
       - Intermediate steps for difficult transitions
       - Additional resources or support materials
       - Alternative completion paths for flexibility
    
    <Note>
    Changes to active journeys will apply to all currently enrolled members by default. Use the **Apply to New Members Only** option if you don't want to affect current participants.
    </Note>
  </Accordion>
</AccordionGroup>

## Collecting Member Feedback

Member feedback is invaluable for journey optimization:

<Steps>
  <Step title="Enable Feedback Collection">
    1. Go to **Journey Settings > Feedback**
    2. Toggle on **Collect Stage Feedback**
    3. Choose between:
       - Quick ratings (1-5 stars)
       - Short form responses
       - Detailed surveys
  </Step>
  
  <Step title="Review Feedback">
    1. Access **Journey Analytics > Member Feedback**
    2. Filter by journey, stage, or date range
    3. Review quantitative ratings and qualitative comments
  </Step>
  
  <Step title="Implement Improvements">
    1. Identify common themes in feedback
    2. Prioritize changes based on impact and frequency
    3. Use **Journey Versioning** to test variations
    4. Monitor metrics to confirm improvement
  </Step>
</Steps>

## Reporting and Sharing Insights

### Regular Reports

Configure automated reports to keep your team informed:

1. Go to **Analytics > Report Settings**
2. Select **Journey Performance**
3. Choose report frequency (daily, weekly, monthly)
4. Select recipients and delivery method

### Exporting Data

For custom analysis or presentation:

1. From any Journey Analytics page, click **Export**
2. Choose format (CSV, Excel, PDF)
3. Select data range and metrics to include
4. Use for team meetings, investor presentations, or integration with other business intelligence tools

## Next Steps

<Cards>
  <Card title="Journey Templates" icon="clone" href="/guides/journeys/journey-templates">
    Explore pre-built journey frameworks for quick implementation
  </Card>
  <Card title="Member Engagement Best Practices" icon="users" href="/guides/engagement/communication-strategy">
    Learn more about effective member communication strategies
  </Card>
</Cards> 