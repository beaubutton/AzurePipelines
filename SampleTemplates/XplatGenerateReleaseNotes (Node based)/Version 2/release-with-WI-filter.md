## Notes for release  ${releaseDetails.releaseDefinition.name}    
**Release Number**  : ${releaseDetails.name}    
**Release completed** : ${releaseDetails.modifiedOn}     
**Compared Release Number**  : ${compareReleaseDetails.name}    

### All associated work items  
@@WILOOP@@  
* ** ${widetail.fields['System.WorkItemType']} ${widetail.id} ** Assigned by: ${widetail.fields['System.AssignedTo']}  ${widetail.fields['System.Title']}  
@@WILOOP@@  

### Associated work items with 'Tag 1' 
@@WILOOP:TAG 1@@  
* ** ${widetail.fields['System.WorkItemType']} ${widetail.id} ** Assigned by: ${widetail.fields['System.AssignedTo']}  ${widetail.fields['System.Title']}  
@@WILOOP:TAG 1@@  

### Associated work items with 'Tag 1' and 'Tag 2' 
@@WILOOP:TAG 1:TAG2@@  
* ** ${widetail.fields['System.WorkItemType']} ${widetail.id} ** Assigned by: ${widetail.fields['System.AssignedTo']}  ${widetail.fields['System.Title']}  
@@WILOOP:TAG 1:TAG2@@    
  
### Associated commits
@@CSLOOP@@  
* ** ID ${csdetail.id} ** ${csdetail.message}    
@@CSLOOP@@
