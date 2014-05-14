Classified tweaks
=================

Some tweaks to enhance the usability of [Classified Ads][1] by removing
some of the options and adding some extra features.

* Removed display of expiration options and fieldset on node/add, node/active
  ad/edit, node/expired ad/edit.

* Added manual, pre-expire unpublish button. This allows users to take their
  ad offline but still keep it for later use.

* Added “force expire.” All ads are forced to complete their assigned
  expiration dates. Once expired they can be re-published.

* Added “force new post date” for expired ads that have been reposted/renewed.
  Allows ads to be bumped back to the top of search results.

* Added “disable Ad Category” after node/add. This prevents users from changing
  the Ad Category which would mess up the expiry.

* Added expiry notifications at the top of each content phase (node/add,
  node/active ad/edit, node/expired ad/edit). This informs the user when the ad
  will expire and when the ad has expired with included new button options such
  as “Renew”, “Republish”, “Unpublish”, “Keep unpublished”, “Save”, “Delete”,
  and “Cancel.”

See https://drupal.org/comment/8375163 for more background.

Known Issues
------------

Does not currently work with [Content Approval][4]. Some lite testing has been
done and so far it cannot be confirmed which module is the issue. Authors have
no more requirement for content approval. Therefore no further testing will be
done.

Authors
-------

Developed by [Capi Etheriel][2].
Idea and sponsorship by [System Lord Mark][3].

[1]: https://drupal.org/project/ed_classified
[2]: https://drupal.org/user/511760
[3]: https://drupal.org/user/2734905
[4]: https://drupal.org/project/content_approval
