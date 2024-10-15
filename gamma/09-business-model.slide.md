---

## **Slide Title: Business Model**

---

### **Dual Revenue Streams**

1. **Subscription Plans**

    - **Free Tier**
        - **Price:** $0 per user/month
        - **User Limit:** Up to 10 users per organization
        - **Features:** Basic access to PlantonCloud's platform

    - **Team Plan**
        - **Price:** $29 per user/month
        - **User Limit:** Up to 100 users
        - **Features:**
            - Advanced platform features
            - Team collaboration tools
            - Standard support

    - **Pro Plan**
        - **Price:** $99 per user/month
        - **User Limit:** Over 100 users
        - **Features:**
            - All Team Plan features
            - Enterprise-grade security
            - Dedicated support
            - Custom integrations

2. **Usage-Based Charges**

    - **Stack Job Runner (SJR) Minutes**
        - **What It Is:** Compute time consumed by CI/CD operations
        - **Pricing:** $10 per 100 minutes
        - **How It Works:**
            - Organizations start with zero SJR minutes each month
            - Minutes accumulate with each deployment, update, or deletion
            - Users purchase additional minutes as needed

    - **Pulumi Active Resource Count**
        - **What It Is:** Number of active infrastructure resources managed
        - **Pricing:** $0.0001 per resource per hour (example rate)
        - **How It Works:**
            - Active resources are counted hourly
            - Counts are accumulated over the billing period
            - Charges reflect actual resource utilization

---

### **Presenter Notes**

**Introduction:**

- **Overview:**
    - PlantonCloud's business model combines subscription-based revenue with usage-based charges, aligning costs with
      customer value and usage.

**1. Subscription Plans:**

- **Free Tier:**

    - **Target Audience:**
        - Ideal for startups and small teams beginning their journey with PlantonCloud.
    - **Features and Limitations:**
        - Access to basic features to deploy and manage applications.
        - Limited to 10 users per organization.
        - Serves as an entry point to showcase the platform's value.

- **Team Plan ($29 per user/month):**

    - **Target Audience:**
        - Suited for growing organizations with up to 100 users.
    - **Features:**
        - Includes advanced platform capabilities.
        - Team collaboration tools enhance productivity.
        - Standard support ensures smooth operations.
    - **Benefits:**
        - Scales with organizational growth.
        - Provides better control and management features.

- **Pro Plan ($99 per user/month):**

    - **Target Audience:**
        - Designed for large enterprises with over 100 users.
    - **Features:**
        - All features from the Team Plan.
        - Enterprise-grade security and compliance features.
        - Dedicated support with priority response times.
        - Custom integrations with existing enterprise systems.
    - **Benefits:**
        - Meets the complex needs of large organizations.
        - Offers peace of mind with enhanced security and support.

**2. Usage-Based Charges:**

- **Stack Job Runner (SJR) Minutes:**

    - **Understanding SJR Minutes:**
        - Represents the compute time consumed during CI/CD pipeline executions (stack jobs) for deployments, updates,
          and deletions.
    - **How It Works:**
        - Organizations start each month with zero SJR minutes.
        - Every stack job consumes minutes based on its execution time.
        - Example: Deploying an AWS RDS instance may consume 10 minutes, while deploying a Redis instance on Kubernetes
          may consume less than a minute.
    - **Pricing Model:**
        - Minutes are purchased in packs (e.g., 100 minutes for $10).
        - Allows organizations to scale their usage based on actual needs.
    - **Benefits:**
        - Aligns costs with deployment activity.
        - Encourages efficient use of CI/CD resources.

- **Pulumi Active Resource Count:**

    - **Understanding Active Resource Count:**
        - Counts the number of active infrastructure resources managed by PlantonCloud at any given hour.
        - Examples of resources include Kubernetes deployments, services, AWS resources like RDS instances, etc.
    - **How It Works:**
        - Active resources are counted hourly throughout the billing period.
        - The cumulative resource count is calculated by summing the hourly counts.
        - Example:
            - Hour 1: 0 resources
            - Hour 2-4: 12 resources (after deploying Redis)
            - Hour 5 onward: 32 resources (after adding Kafka)
        - Even if resources are destroyed, the accumulated usage up to that point is billed.
    - **Pricing Model:**
        - Charged at a rate per resource per hour (e.g., $0.0001 per resource per hour).
        - Reflects actual infrastructure usage over time.
    - **Benefits:**
        - Provides transparency in billing.
        - Costs scale with the organization's infrastructure footprint.
        - Encourages optimization of resource usage.

**Conclusion:**

- **Scalable and Flexible Pricing:**

    - Our dual revenue streams ensure that organizations only pay for what they need and use.
    - Subscription plans offer predictable costs based on team size and required features.
    - Usage-based charges reflect actual platform utilization, providing cost-efficiency.

- **Alignment with Customer Value:**

    - By tying costs to usage and resource consumption, we align our revenue model with the value delivered to
      customers.
    - This model supports organizations of all sizes, from startups to large enterprises.

- **Revenue Growth Potential:**

    - As customers grow and their usage of PlantonCloud increases, our revenue scales accordingly.
    - The model supports upselling opportunities as organizations move from the Free Tier to Team and Pro Plans.
    - Usage-based charges provide a continuous revenue stream that grows with customer adoption.

**Additional Points:**

- **Competitive Advantage:**

    - Our flexible pricing model differentiates us from competitors who may have rigid or less transparent pricing
      structures.
    - Encourages adoption by lowering the barrier to entry and scaling costs with actual needs.

- **Customer Retention:**

    - By providing value-aligned pricing, we foster long-term relationships with customers.
    - The model incentivizes customers to stay and grow with PlantonCloud.

---

**Note for Presentation:**

- **Visual Aids:**

    - Include a pricing table or chart summarizing the subscription plans and their features.
    - Use graphs or illustrations to depict how usage-based charges accumulate and align with activity.
    - Provide example scenarios showing cost calculations for typical usage patterns.

- **Engagement Tips:**

    - Emphasize how the business model benefits both the company and the customers.
    - Highlight the flexibility and scalability of the pricing structure.
    - Be prepared to address questions regarding how pricing compares to competitors and the value proposition.
