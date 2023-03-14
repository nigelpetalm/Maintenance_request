<template>
  <div>
    <table>
      <table>
  <tr>
    <th>Date</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td><input id="date" name="date" type="date" required /></td>
      <label for="problem">Write your problem here:
        <textarea id="problem" name="name" rows=3 cols="30" placeholder="i have a problem with logging in">
        </textarea>
    </label>
    <td><label for="status" name="status">
      <option value="">(Select One)</option>
      <option value="1">Completed</option>
      <option value="2">Not Completed</option>
      <option value="3">Pending</option>
    </label></td>
  </tr>
</table>
    </table>
    <input type="submit" value="submit" />
  </div>
</template>
