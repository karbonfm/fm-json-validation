## JSON.Validate.This ( json)```/**
 *
 * sets the JSON to validate into a known var
 *
 * @param {object} JSON 
 * 
 * @author Todd Geist, https://github.com/toddgeist
 * @module JSON.Validate
 * @see https://github.com/karbonfm/fm-json-validation
 */```## JSON.Validate.Rule.IsRequired ( path)```/**
 *
 * A rule that tests for a value at the path
 *
 * @param {string} path the path to the value to test
 *
 * @returnSuccess {string} ""  / nothing
 * @returnError {object} JSON.Validate.Error an error
 * 
 * @author Todd Geist, https://github.com/toddgeist
 * @module JSON.Validate
 * @see https://github.com/karbonfm/fm-json-validation
 *
 */```## JSON.Validate.Rule.IsOneOf ( path;theList)```/**
 *
 * A rule that test if a value is in a list
 *
 * @param {string} path the path to the value to test
 * @param {string} theList carraige return deliminated list
 *
 * @returnSuccess {string} ""  / nothing
 * @returnError {object} JSON.Validate.Error an error
 * 
 * @author Todd Geist, https://github.com/toddgeist
 * @module JSON.Validate
 * @see https://github.com/karbonfm/fm-json-validation
 *
 */```## JSON.Validate.ApplyRules ( ListOfRules)```/**
 *
 * Applies a list of Rules to the JSON set by JSON.Validate.This()
 *
 * @param {string} ListOfRule the list of rules made with List(JSON.Validate.Rule.<x>)
 *
 * @returnSuccess {string} ""  / nothing
 * @returnError {object} JSON.Validate.Error an error
 * 
 * @author Todd Geist, https://github.com/toddgeist
 * @module JSON.Validate
 * @see https://github.com/karbonfm/fm-json-validation
 *
 */```## JSON.Validate._Error ( path;message)```/**
 *
 * creates a JSON Validate error
 *
 * @param {object} JSON 
 * 
 * @returns {object} error
 *
 * @private
 * @module JSON.Validate
 * @see https://github.com/karbonfm/fm-json-validation
 *
 */```