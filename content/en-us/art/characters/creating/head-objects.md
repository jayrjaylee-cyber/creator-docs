---

<table>
  <tr>
    <th>Title</th>
    <td>Build the Face: Understanding the Roblox Head Structure</td>
  </tr>
  <tr>
    <th>Description</th>
    <td>Every great Roblox avatar starts with the right structure! Explore how separate modular head pieces work together and learn which parts to combine, adjust, or remove to create a seamless character design.</td>
  </tr>
  <tr>
    <th>Next</th>
    <td>/art/characters/creating/blender-configurations</td>
  </tr>
  <tr>
    <th>Prev</th>
    <td>/art/characters/creating/template-</td>
  </tr>
</table>

files
---

Each avatar character body template includes extra head mesh objects and face armature bones. Separating these objects within the templates allows you to make easier changes to each of these separate objects, as demonstrated during the texturing section of this tutorial.

To avoid validation errors, you must [join](../../../art/characters/creating/combine-head-geometry.md) and [remove](../../../art/characters/creating/remove-extra-bones.md) these extra objects during the cleanup process prior to exporting.

The extra head mesh objects are the following:
<GridContainer numColumns="2">

  <figure>
   - Head_Geo
   - UpperTeeth_Geo
   - LowerTeeth_Geo
   - Tongue_Geo
   - RightLash_Geo
   - RightEye_Geo
   - LeftLash_Geo
   - LeftEye_Geo
</figure>

  <figure><img
  alt="Head-Related Meshes"
  src="../../../assets/art/blender-ui/Face-Objects.png"
  width="800" /><figcaption>Extra head-related meshes in Blender's Outliner</figcaption></figure>
</GridContainer>

<p />

The extra head bone children are the following and may differ between templates:

<GridContainer numColumns="2">

  <figure>
   - Tongue
   - LowerTeeth
   - UpperTeeth
   - LeftEye
   - RightEye
</figure>

  <figure><img
  alt="Head-Related Meshes"
  src="../../../assets/art/blender-ui/Face-Bones.png"
  width="800" /><figcaption>Extra head-related bones in Blender's Outliner</figcaption></figure>
</GridContainer>

While these extra objects exist to aid the creation and modification process, leaving them in your project on final export will cause validation issues when uploading these assets to the Marketplace.
