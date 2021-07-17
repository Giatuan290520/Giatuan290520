<form name="maytinh">
    <table>
      <tr>
        <td colspan="4">
          <input type="text" name="display" disabled>
        </td>
      </tr>
      <tr>
        <td><input type="button" name="one" value="1" onclick="maytinh.display.value += 1"></td>
        <td><input type="button" name="two" value="2" onclick="maytinh.display.value += 2"></td>
        <td><input type="button" name="three" value="3" onclick="maytinh.display.value += 3"></td>
        <td><input type="button" class="operator" name="plus" value="+" onclick="maytinh.display.value += '+'"></td>
      </tr>
      <tr>
        <td><input type="button" name="four" value="4" onclick="maytinh.display.value += 4"></td>
        <td><input type="button" name="five" value="5" onclick="maytinh.display.value += 5"></td>
        <td><input type="button" name="six" value="6" onclick="maytinh.display.value += 6"></td>
        <td><input type="button" class="operator" name="minus" value="-" onclick="maytinh.display.value += '-'"></td>
      </tr>
      <tr>
        <td><input type="button" name="seven" value="7" onclick="maytinh.display.value += 7"></td>
        <td><input type="button" name="eight" value="8" onclick="maytinh.display.value += 8"></td>
        <td><input type="button" name="nine" value="9" onclick="maytinh.display.value += 9"></td>
        <td><input type="button" class="operator" name="times" value="x" onclick="maytinh.display.value += '*'"></td>
      </tr>
      <tr>
        <td><input type="button" class="operator" id="clear" name="clear" value="C" onclick="maytinh.display.value = ''"></td>
        <td><input type="button" class="operator" name="zero" value="0" onclick="maytinh.display.value += '0'"></td>
        <td><input type="button" class="operator" name="doit" value="=" onclick="maytinh.display.value = eval(maytinh.display.value)"></td>
        <td><input type="button" class="operator" name="div" value="/" onclick="maytinh.display.value += '/'"></td>
      </tr>
    </table>
  </form>
