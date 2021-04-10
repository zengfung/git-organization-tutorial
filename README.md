# GitHub Organizations & GitLab Groups Tutorial

This is a very brief and quick tutorial on how to set up and navigate organizations and groups in GitHub and GitLab respectively. The information from this tutorial are obtained and summarized from  
* GitHub Organizations documentation: [https://docs.github.com/en/organizations](https://docs.github.com/en/organizations)
* GitLab Groups documentation: [https://docs.gitlab.com/ee/user/group/](https://docs.gitlab.com/ee/user/group/)

# Table of Contents
1. [GitHub Organizations](#github)  
    * [Creating a New Organization From Scratch](#github-neworg)
    * [Navigate to an Existing Organization](#github-existingorg)
    * [Deleting/Renaming an Organization](#github-deleterename)
    * [Inviting and Managing Members](#github-members)
    * [Add Pre-existing Repositories to Organization](#github-addrepo)
2. [GitLab Groups](#gitlab)
    * [Creating a New Organization From Scratch](#github-newgroup)
    * [Navigate to an Existing Organization](#gitlab-existinggroup)
    * [Deleting/Renaming an Organization](#gitlab-deleterename)
    * [Inviting and Managing Members](#gitlab-members)
    * [Add Pre-existing Repositories to Organization](#gitlab-addrepo)

# GitHub Organizations <a name="github"></a>
## Creating a New Organization From Scratch <a name="github-neworg"></a>
1. Navigate to the **Select Plan** page.  
**Method 1:**  
a. Click on your profile photo on the top-right corner of any of your Github page, then select **Settings**.
![](images/github-org-getsettings.PNG)  
b. In the user settings sidebar on the left, click on **Organizations**.  
c. Click on **New organization**.  
![](images/github-org-new1.PNG)  
**Method 2:**  
a. Click on the **+** drop-down menu on the top-right corner of any of your Github page, then select **New organization**.
![](images/github-org-new2.PNG)

4. This will then prompt you to select a plan for your team or organization. The current plan is summarized as follows:  
 <table>
<tr>
    <th></th>
    <th>Free</th>
    <th>Team</th>
    <th>Enterprise</th>
</tr>
<tr>
    <td><b>Price</b></td>
    <td><li>$0</li></td>
    <td><li>$4 per user/month</li></td>
    <td><li>$21 per user/month</li></td>
</tr>
<tr>
    <td><b>Benefits</b></td>
    <td>
        <li>Unlimited public/private repositories</li>
        <li>Unlimited collaborators</li>
        <li>2,000 Actions minutes/month (Free for public repositories)</li>
        <li>500MB GitHub Packages</li>
        <li>Community Support</li>
    </td>
    <td>
        <li>Unlimited public/private repositories</li>
        <li>Unlimited collaborators</li>
        <li>3,000 Actions minutes/month (Free for public repositories)</li>
        <li>2GB GitHub Packages</li>
        <li>Community Support</li>
        <li>Required reviewers</li>
        <li>Code owners</li>
    </td>
    <td>
        <li>Unlimited public/private repositories</li>
        <li>Unlimited collaborators</li>
        <li>50,000 Actions minutes/month (Free for public repositories)</li>
        <li>50GB GitHub Packages</li>
        <li>Community Support</li>
        <li>Required reviewers</li>
        <li>Code owners</li>
        <li>SAML single sign-on</li>
        <li>Advanced auditing</li>
    </td>
</tr>
</table>

Depending on the size of the organization and projects, the **Free** and **Team** plans should suffice.

5. Set up the organization by filling up the following:
![](images/github-org-setup.PNG)

6. Invite members to the organization to complete the set up process.
![](images/github-org-invites.PNG)

7. Once you're done, you should see a page that looks like this:
![](images/github-org-complete.PNG)

## Navigating to an Existing Organization <a name="github-existingorg"></a>
1. Click on your profile photo on the top-right corner of any of your Github page, then select **Your profile**.  
![](images/github-org-yourprofile.PNG)  
2. On the left side of your profile page, click on the icon of your organization under **Organizations**.
![](images/github-org-toorg.PNG)
## Deleting/Renaming an Organization <a name="github-deleterename"></a>
1. Navigate to your organization page, click **Settings**.  
![](images/github-org-orgsettings.PNG)
2. Scroll all the way down to **Danger zone** and click on **Delete this organization** or **Rename organization** depending on your needs.  
![](images/github-org-deleteorg.PNG)

## Inviting and Managing Members <a name="github-members"></a>
1. Navigate to your organization page, click **People**.  
![](images/github-org-orgsettings.PNG)
2. New members can be invited by clicking on **Invite member**, while current members can be managed from the settings button in the member list.  
![](images/github-org-managepeople.PNG)

For more information on managing members in a GitHub organization, please visit [this link](https://docs.github.com/en/enterprise-server@3.0/organizations/managing-membership-in-your-organization/adding-people-to-your-organization).

## Add Pre-existing Repositories to Organization <a name="github-addrepo"></a>
Assuming that we have some pre-existing repositories on individual accounts that we want to add to the organization, we can do the following:  
1. Navigate to the repository and click on **Settings**.
![](images/github-org-reposettings.PNG)
2. Scroll all the way down to the **Danger zone** and click on **Transfer ownership**.  
![](images/github-org-transferownership.PNG)

# GitLab Groups <a name="gitlab"></a>
## Creating a New Group from Scratch <a name="gitlab-newgroup"></a>
1. After logging into GitLab, you can access the **Groups** drop-down menu on the top left of your screen.
![](images/gitlab-group-navigate.PNG)  
2. You can either navigate to **Your groups** then click on **New group**, or you can click on **Create group** to directly reach the following page:  
![](images/gitlab-group-newgroup.PNG)
Fill up this page and click **Create group** and you're good to go.

## Navigating to an Existing Group <a name="gitlab-existinggroup"></a>
Navigating to an existing Group by clicking on **Your groups** from the **Groups** drop-down menu on the top left of your screen.  
![](images/gitlab-group-navigate.PNG)
## Deleting/Renaming a Group <a name="gitlab-deleterename"></a>
1. Navigate to an existing group. On the menu on the left side of your screen, click **Settings**  &#8594; **General**.  
![](images/gitlab-group-settings.PNG)
2. Your group can be renamed under **Naming, visibility** section as shown.  
![](images/gitlab-group-rename.PNG)  
To delete a Group, scroll all the way down and expand the **Advanced** section, then scroll all the way down once again until you see the **Remove group** section.  
![](images/gitlab-group-remove.PNG)

## Inviting and Managing Members <a name="gitlab-members"></a>
1. From the left menu, select **Members**.
2. You can invite collaborators/groups into your pre-existing group by filling up the necessary details at the top of the page.  
![](images/gitlab-group-invite.PNG)
3. To delete members, scroll down until you see the **Members** list. Next to the member you want to remove, select **Delete** &#8594; **Remove member**.  
For more info on removing group members, follow [this link](https://docs.gitlab.com/ee/user/group/#remove-a-member-from-the-group).

## Add Pre-existing Repositories to Organization <a name="gitlab-addrepo"></a>
Assuming that we have some pre-existing repositories on individual accounts that we want to add to the group, we can do the following:  
1. Navigate to the repository and click on **Settings** &#8594; **General**. 
2. Scroll all the way down and expand the **Advanced** section, then scroll all the way down once again until you see the **Remove group** section. 
![](images/gitlab-group-transferrepo.PNG)
3. Select the group you want to transfer to under **Select a new namespace**.