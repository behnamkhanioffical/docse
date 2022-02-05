Key | Type | Description
----|------|-------------
`action`|`string` | The action that was performed. Can be one of:<ul><li>`assigned`</li>{% ifversion fpt or ghes > 3.0 or ghae or ghec %}<li>`auto_merge_disabled`</li><li>`auto_merge_enabled`</li>{% endif %}<li>`closed`: If the action is `closed` and the `merged` key is `false`, the pull request was closed with unmerged commits. If the action is `closed` and the `merged` key is `true`, the pull request was merged.</li><li>`converted_to_draft`</li><li>`edited`</li><li>`labeled`</li><li>`locked`</li><li>`opened`</li><li>`ready_for_review`</li><li>`reopened`</li><li>`review_request_removed`</li><li>`review_requested`</li><li>`synchronize`: Triggered when a pull request's head branch is updated. For example, when the head branch is updated from the base branch, when new commits are pushed to the head branch, or when the base branch is changed.</li><li>`unassigned`</li><li>`unlabeled`</li><li>`unlocked`</li></ul>